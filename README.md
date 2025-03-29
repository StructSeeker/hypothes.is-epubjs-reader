# A epub Reader that allow hypothes.is

This cloud-based epub reader allow hypothes.is browser extension (chrome on pc, kiwibroswer on android, resp.) to be run for particular uploaded epub book.

Read your epub file using the top-right upload button, the file is not transmitted to any remote server.

[Try it](https://structseeker.github.io/hypothes.is-epubjs-reader/)!



## Features

**Embedded hypothes.is:** Enjoy Annotation Service on any browser, espcially mobile device.  

**More Readable Title:** The epub title is injected before the page title, making it more viewable in your hypothes.is record.   

**Read Epub From Internet:** Use the following scheme to directly read epub from internet.
    `https://structseeker.github.io/hypothes.is-epub.js-reader/index.html?bookPath=http://url.com/path/book.epub`  
    `https://structseeker.github.io/hypothes.is-epub.js-reader/index.html?bookPath=http://url.com/if/your/download/link/doesnot/end/with/dot/epub/then/add/urlparam/?x.epub`  
Note it won't work if the targeted epub source doesn't have `Access-Control-Allow-Origin: *` in response header, You need [bypass CORS restrictions](https://chromewebstore.google.com/search/cors) to allow it.


**Caution:**  Make sure that the uploaded epub is safe!

**ToDo**  
 - [x] Fix upstream UI Bugs.   
 - [ ] Fix the security flaw.


