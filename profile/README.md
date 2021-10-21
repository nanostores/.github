A tiny state manager for **React**, **React Native**, **Preact**, **Vue**,
**Svelte**, and vanilla JS. It uses **many atomic stores**
and direct manipulation.

* **Small.** between 198 and 878 bytes (minified and gzipped).
  Zero dependencies. It uses [Size Limit] to control size.
* **Fast.** With small atomic and derived stores, you do not need to call
  the selector function for all components on every store change.
* **Tree Shakable.** The chunk contains only stores used by components
  in the chunk.
* Was designed to move logic from components to stores.
* It has good **TypeScript** support.
