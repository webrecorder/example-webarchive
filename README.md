This is a simple example of how to self-host web archives on your website. You can see it in action at https://webrecorder.github.io/example-webarchive/ Documentation for how things work is available [here](https://replayweb.page/docs/embedding). It's just HTML, CSS, JavaScript and [WACZ](https://specs.webrecorder.net/wacz/latest/) created with [Webrecorder](https://webrecorder.net) tools.

```
.
├── README.md
├── css
│   └── style.css
├── images
│   ├── birth-web.png
│   ├── whitehouse.png
│   └── www-talk.png
├── index.html
├── items
│   ├── birth-web
│   │   ├── archive.wacz
│   │   └── index.html
│   ├── whitehouse
│   │   ├── archive.wacz
│   │   └── index.html
│   └── www-talk
│       ├── archive.wacz
│       └── index.html
└── js
    ├── sw.js
    └── ui.js
```
