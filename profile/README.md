A tiny state manager for **React**, **React Native**, **Preact**, **Vue**,
**Svelte**, **Solid**, **Lit**, **Angular** and vanilla JS. It uses **many atomic stores**
and direct manipulation.

* **Small.** Less than 1 KB. Zero dependencies.
* **Fast.** With small atomic and derived stores, you do not need to call
  the selector function for all components on every store change.
* **Tree Shakable.** The chunk contains only stores used by components
  in the chunk.
* Was designed to move logic from components to stores.
* It has good **TypeScript** support.

It has many smart stores with built-in logic inside:

* [Async computed](https://github.com/nanostores/async) store
  to fetch data or create chains of async operations.
* [Persistent](https://github.com/nanostores/persistent) store to save data
  to `localStorage` and synchronize changes between browser tabs.
* [Router](https://github.com/nanostores/router) store to parse URL
  and implements SPA navigation.
* [Deep Map](https://github.com/nanostores/deepmap) store to put
  big nested object/arrays and change keys by path.
* [I18n](https://github.com/nanostores/i18n) library based on stores
  to make application translatable.
* [Query](https://github.com/nanostores/query) store that helps you with smart
  remote data fetching.
* [Logux Client](https://github.com/logux/client): stores with WebSocket
  sync and CRDT conflict resolution.
* [Immer](https://github.com/illuxiza/nanostores-immer) plugin to
  enable immutable state updates using Immer.
