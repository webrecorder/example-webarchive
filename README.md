This is a simple example of how to self-host web archives on your website. You can see it in action at https://webrecorder.github.io/example-webarchive/ Documentation for how things work is available [here](https://replayweb.page/docs/embedding). It's just HTML, CSS, JavaScript and [WACZ](https://specs.webrecorder.net/wacz/latest/) created with [Webrecorder](https://webrecorder.net) tools.

You can see that the `ui.js` and `sw.js` files that are required for the `&lt;replay-web-page&gt;` component to work are centrally located so that the Service Worker scope includes the pages with embedded archives. Each page has its associated WACZ file.

```
.
├── css
│   └── style.css
├── images
│   ├── birth-web.png
│   ├── whitehouse.png
│   ├── wikipedia.png
│   └── www-talk.png
├── index.html
└── items
    ├── ui.js
    ├── sw.js
    ├── birth-web
    │   ├── archive.wacz
    │   └── index.html
    ├── wikipedia
    │   ├── archive.wacz
    │   └── index.html
    └── www-talk
        ├── archive.wacz
        └── index.html
