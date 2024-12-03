# About this Fork

This is the codebase for the tutorial at https://developers.google.com/codelabs/pwa-training/pwa03--going-offline#0, 
but instead of using node for the server, it uses Symfony and spomky-labs/pwa-bundle

In addition to using generated sw.js and manifest files, the api call to get events comes from the server, and could come from a database.  An exercise would be to keep the postgres database and client in sync.

Ideas:

* https://rxdb.info/
* Api Platform
* https://github.com/anchetadev/PWA-IndexedDB-Guide
* https://medium.com/jspoint/indexeddb-your-second-step-towards-progressive-web-apps-pwa-dcbcd6cc207
* https://medium.com/@adamrackis/making-your-web-app-work-offline-with-service-workers-and-indexeddb-6ce9c538c48

To run locally, install the Symfony CLI and PHP 8

```bash
```
# Data driven PWA

In this codelab, you’ll use [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) and [Workbox](https://workboxjs.org/) to create a fully offline-capable, data-driven app. You'll also use [Background Sync](https://developers.google.com/web/updates/2015/12/background-sync) to sync your app with the server even when your web app is closed.

## Getting started

Follow the [Google Codelabs instructions](https://codelabs.developers.google.com/codelabs/workbox-indexeddb/index.html?index=..%2F..%2Findex#0).

## More resources

* IndexedDB [lecture](https://developers.google.com/web/ilt/pwa/working-with-indexeddb-slides), [lab](https://developers.google.com/web/ilt/pwa/lab-indexeddb), and [concepts](https://developers.google.com/web/ilt/pwa/working-with-indexeddb)
* [Workbox codelab](https://codelabs.developers.google.com/codelabs/workbox-lab/#0)
* [PWA training materials](https://developers.google.com/web/ilt/pwa/)

## License

Copyright 2016 Google Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

This is not an official Google product.
