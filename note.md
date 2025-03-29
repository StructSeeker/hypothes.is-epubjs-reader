# Modify Title

```
let iframe = document.querySelector('.epub-view > iframe')
let iframedoc = iframe.contentWindow.document

iframe.onload = () => {
    iframedoc.querySelector('title').prepend(document.querySelector('title').innerHTML);
}

```

