## Electron Plugin bundling issue

### Repro steps

* Copy `widevinecdmadapter.plugin` and `libwidevinecdm.dylib` to `/tmp`

* `npm install`
* `npm start` finds and loads the plugins correctly
* `npm build`
* `npm start-app` doesn't find the plugin
