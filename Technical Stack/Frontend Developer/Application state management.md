Application state management
============================

[Redux](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux)
----------------------------------------------------------------------------------------

*   [ ] You can describe full Redux flow [:books:](https://redux.js.org/tutorials/fundamentals/part-2-concepts-data-flow)
*   [ ] You know how to dispatch Redux action (outside React context) [:books:](https://redux.js.org/tutorials/fundamentals/part-4-store#dispatching-actions)
*   [ ] You know what it does and can use <code>combineReducers</code> function [:books:](https://redux.js.org/tutorials/fundamentals/part-3-state-actions-reducers#combinereducers)
*   [ ] You know how to apply a middleware / enhancer when creating redux store [:books:](https://redux.js.org/understanding/history-and-design/middleware#the-final-approach)
*   [ ] You know what is a difference between middleware and enhancer [:books:](https://read.reduxbook.com/markdown/part1/05-middleware-and-enhancers.html)

### [react-redux](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#react-redux)

*   [ ] You know how to apply selector functions to <code>useSelector</code> hook. [:books:](https://levelup.gitconnected.com/react-redux-hooks-useselector-and-usedispatch-f7d8c7f75cdd)
*   [ ] You know how to dispatch actions from React component. [:books:](https://redux.js.org/basics/example)
*   [ ] You know how to implement your own <code>connect</code> higher order component [:books:](https://redux.js.org/usage/usage-with-typescript#typing-the-connect-higher-order-component)

### [Redux toolset](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-toolset)

*   [ ] You can use one of the listed toolset libraries to create reducers, action types, and action creators more efficiently [:books:](https://redux-toolkit.js.org/usage/usage-guide#writing-action-creators)

#### [redux-toolkit](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-toolkit)

*   [ ] You know how to create a reducer. [:books:](https://redux-toolkit.js.org/tutorials/basic-tutorial)
*   [ ] You know how to create an action creator [:books:](https://redux-toolkit.js.org/usage/usage-guide#writing-action-creators)
*   [ ] You understand how to leverage the fact that action creators serialize to action's type string.
*   [ ] You know how to define a reducer function for a specific action type. [:books:](https://redux-toolkit.js.org/usage/usage-guide#writing-reducers)
*   [ ] You know how to use slices [:books:](https://redux-toolkit.js.org/rtk-query/api/created-api/overview#api-slice-overview)

#### [reduxsauce](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#reduxsauce)

*   [ ] You know how to create reducers [:books:](https://www.npmjs.com/package/reduxsauce)
*   [ ] You can create your own action creators and action types.

#### [redux-persist](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-persist)

*   [ ] You know how to persist part of the state tree to local storage

## [Zustand](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#zustand)

*   [ ] You know how to use zustand as a application state management. [:books:](https://github.com/pmndrs/zustand)

[Immutable data structures](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#immutable-data-structures)
--------------------------------------------------------------------------------------------------------------------------------

*   [ ] You understand benefits of using immutable data structures in Redux applications [:books:](https://medium.com/javascript-in-plain-english/why-react-and-redux-need-immutable-data-dae3ab3611a0)
*   [ ] You know how to use at least one of the libraries that provide immutable data structures in redux state [:books:](https://css-tricks.com/using-immer-for-react-state-management/)

### [immer](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#immer)

*   [ ] You know how to create a reducer that uses immer [:books:](https://hackernoon.com/introducing-immer-immutability-the-easy-way-9d73d8f71cb3)
*   [ ] You know how to convert immutable structure to regular JavaScript object
*   [ ] You know the difference between only changing state object and returning a changed state object
*   [ ] You can explain how immer works internally.

### [Immutable.js](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#immutable.js)

*   [ ] You know how to create an immutable structure [:books:](https://www.freecodecamp.org/news/immutable-js-is-intimidating-heres-how-to-get-started-2db1770466d6/)
*   [ ] You know how to read data from the immutable structure
*   [ ] You know how to create a new data structure with modified state out of an existing one
*   [ ] You know how to use the store with immutable structures using <code>redux-immutable</code> [:books:](https://redux.js.org/recipes/using-immutablejs-with-redux)
*   [ ] You know how to convert a json structure into immutable structure, and vice-versa
*   [ ] You know how to manipulate big structures and which operations you should avoid in order to keep performance

### [seamless-immutable](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#seamless-immutable)

*   [ ] You know how to read data from the immutable structure
*   [ ] You know how to create a new data structure with modified state out of an existing one
*   [ ] You understand the difference between <code>immutable.js</code> and <code>seamless-immutable</code> [:books:](https://medium.com/@ckoster22/seamless-immutable-an-alternative-to-immutablejs-12795d6bf577)
*   [ ] You know how to transform regular structures into seamless immutable structures, and vice-versa
*   [ ] You know how to reconcile native functions (map, sort, etc) with seamless immutable functions (flatMap, merge, sort, etc)

[Selectors](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#selectors)
------------------------------------------------------------------------------------------------

### [reselect](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#reselect)

*   [ ] You know how to create a selector with <code>createSelector</code> function [:books:](https://medium.com/@pearlmcphee/selectors-react-redux-reselect-9ab984688dd4)
*   [ ] You know how to create a selector that uses multiple other selectors as an input.

[Side effects](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#side-effects)
------------------------------------------------------------------------------------------------------

*   [ ] You understand the concept of side effects [:books:](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0#:~:text=A%20side%20effect%20is%20any,the%20parent%20function%20scope%20chain)

### [redux-saga](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-saga)

*   [ ] You know how to take a side effect and dispatch an action based on it [:books:](https://redux-saga.js.org/docs/api/#putaction)
*   [ ] You know how to run asynchronous functions (e.g. <code>fetch</code>) after something dispatches an action [:books:](https://redux-saga.js.org/docs/basics/DispatchingActions)
*   [ ] You know how to select data from Redux state using selector functions inside sagas. [:books:](https://redux-saga.js.org/docs/api/#selectselector-args)
*   [ ] You understand the concept of Javascript generators [:books:](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators#advanced_generators)
*   [ ] You know how to wait for an another action from inside the running saga. [:books:](https://redux-saga.js.org/docs/api/#takepattern)
*   [ ] You know to sequence Sagas and how to run them in parallel [:books:](https://redux-saga.js.org/docs/advanced/RunningTasksInParallel.html)
*   [ ] You can name <code>eventChannel</code> use cases and know how to implement a saga using it. [:books:](https://redux-saga.js.org/docs/advanced/Channels.html)
*   [ ] You can name <code>actionChannel</code> use cases and know how to implement a saga using it. [:books:](https://redux-saga.js.org/docs/advanced/Channels.html)

#### [redux-saga-routines](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-saga-routines)

*   [ ] You know how to create your own routine
*   [ ] You know how to promisify a routine
*   [ ] You know how to wait for a routine fulfillment inside a component
*   [ ] You understand the advantages of standardizing action type's name
*   [ ] You know how to manipulate the payload with payloadCreator
*   [ ] You know how to enhance the payload with metaCreator

* * *

Contribution
------------

We are very open to contributions to extend or change the requirements based on your gut and experience. To contribute you can use a **pull request** which will be later validated by our technical team and added to the main docs.

If you will spot any issues please add them in the **Issues** section.

Credits
-------

This page is maintained by the 🔹 [Flairs.ai](http://Flairs.ai) and 🇵🇱 [Apptension](https://apptension.com) teams.

If you would like to create a dedicated Developer Handbook for your company, you can e-mail us 👉 [contact@flairs.ai](mailto:contact@flairs.ai)

License
-------

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)

© 2020 Flairs Sp. z o.o.

Built and maintained by [Flairs](https://www.flairs.ai) and [Apptension](https://apptension.com).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
