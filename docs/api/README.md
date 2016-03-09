# API Reference

There aren't a lot of methods and exports, as this - like the Redux API - is
kept minimal. Fluorine defines some paradigms and conventions with which you can
establish your stores and actions. Fluorine itself is just a library of helper
functions that consume these stores and actions.

## Exports

* [createDispatcher()](createDispatcher.md)
* [withActions(dispatcher, actions, [prop])](withActions.md)
* [withStore(store, [prop])](withStore.md)

Depending on whether you use ES6 or not you'll have to use different import
statements:

### ES6

```js
import { createDispatcher } from 'fluorine-lib';
```

### ES5

```js
var createDispatcher = require('fluorine-lib/lib/createDispatcher');
```

## Dispatcher API

* [Dispatcher](dispatcher.md)
  * [dispatch(action)](dispatcher.md#dispatch)
  * [reduce(reducer, init)](dispatcher.md#reduce)
  * [schedule(agenda)](dispatcher.md#schedule)
  * [getState(reducer) *deprecated*](dispatcher.md#getState)
  * [wrapActions(actions)](dispatcher.md#wrapActions)

