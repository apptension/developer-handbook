Application state management
============================

Redux
-----

*   [ ] You can describe full Redux flow [:books:](https://www.youtube.com/watch?v=1w-oQ-i1XB8)
*   [ ] You know how to define a new Redux module (Reducer, Saga, Selector) [:books:](https://github.com/apptension/cra-template-apptension/tree/master/template/src/modules)
*   [ ] You know how to dispatch Redux action (outside React context)

### react-redux

*   [ ] You know how to apply selector functions to <code>useSelector</code> hook. [:books:](https://levelup.gitconnected.com/react-redux-hooks-useselector-and-usedispatch-f7d8c7f75cdd)
*   [ ] You know how to dispatch actions from React component. [:books:](https://redux.js.org/basics/example)

### Redux toolset

*   [ ] You can use one of the toolset libraries to create reducers, action types, and action creators more efficiently

#### redux-toolkit

*   [ ] You know how to create a reducer. [:books:](https://redux-toolkit.js.org/tutorials/basic-tutorial)
*   [ ] You know how to create an action creator [:books:](https://www.johnraptis.dev/redux-toolkit/)
*   [ ] You understand how to leverage the fact that action creators serialize to action's type string.
*   [ ] You know how to define a reducer function for a specific action type.
*   [ ] You know how to use slices

### redux-persist

*   [ ] You know how to persist part of the state tree to local storage

Immutable data structures
-------------------------

*   [ ] You understand benefits of using immutable data structures in Redux applications [:books:](https://medium.com/javascript-in-plain-english/why-react-and-redux-need-immutable-data-dae3ab3611a0)
*   [ ] You know how to use at least one of the libraries that provide immutable data structures in redux state [:books:](https://css-tricks.com/using-immer-for-react-state-management/)

### immer

*   [ ] You know how to create a reducer that uses immer [:books:](https://hackernoon.com/introducing-immer-immutability-the-easy-way-9d73d8f71cb3)
*   [ ] You know how to convert immutable structure to regular JavaScript object
*   [ ] You can explain how immer works internally.

Selectors
---------

### reselect

*   [ ] You know how to create a selector with <code>createSelector</code> function [:books:](https://medium.com/@pearlmcphee/selectors-react-redux-reselect-9ab984688dd4)
*   [ ] You know how to create a selector that uses multiple other selectors as an input.

Side effects
------------

*   [ ] You understand the concept of side effects [:books:](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0#:~:text=A%20side%20effect%20is%20any,the%20parent%20function%20scope%20chain)

### redux-saga

*   [ ] You know how to take a side effect and dispatch an action based on it [:books:](https://redux-saga.js.org/docs/api/#putaction)
*   [ ] You know how to select data from Redux state using selector functions inside sagas. [:books:](https://redux-saga.js.org/docs/api/#selectselector-args)
*   [ ] You understand the concept of Javascript generators [:books:](https://www.youtube.com/watch?v=ategZqxHkz4)
*   [ ] You know to sequence Sagas and how to run them in parallel [:books:](https://redux-saga.js.org/docs/advanced/RunningTasksInParallel.html)
*   [ ] You know how to wait for an another action from inside the running saga. [:books:](https://redux-saga.js.org/docs/api/#takepattern)
*   [ ] You can name <code>eventChannel</code> use cases and know how to implement a saga using it. [:books:](https://redux-saga.js.org/docs/advanced/Channels.html)
*   [ ] You can name <code>actionChannel</code> use cases and know how to implement a saga using it. [:books:](https://redux-saga.js.org/docs/advanced/Channels.html)

#### redux-saga-routines

*   [ ] You know how to create your own routine
*   [ ] You know how to promisify a routine
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