# Modify Title

```
let iframe = document.querySelector('.epub-view > iframe')
let iframedoc = iframe.contentWindow.document

iframe.onload = () => {
    iframedoc.querySelector('title').prepend(document.querySelector('title').innerHTML);
}

```

# Require Cors for bookPath

# Use bookPath treated as folder 

https://github.com/futurepress/epub.js/issues/1320

# Try form

 <input type="text" id="name" name="name"/>