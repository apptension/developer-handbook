Mobile Developer
================

Company best practices
----------------------

### [Security](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#security)

#### [Keeper Security](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#keeper-security)

*   [ ] You know how to share secret values with other employees. [:books:](https://docs.keeper.io/user-guides/)

#### [Onetimesecret](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#onetimesecret)

*   [ ] You know how to share secret values externally [:books:](https://support.painchek.com/hc/en-us/articles/360038504674-How-to-use-One-Time-Secret)

### [Git](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#git)

*   [ ] You create pull requests with proper name and description [:books:](https://medium.com/@hugooodias/the-anatomy-of-a-perfect-pull-request-567382bb6067)
*   [ ] You squash merge your pull requests [:books:](https://blog.pairworking.com/why-you-should-care-about-squash-and-merge-in-git-675856bf66b0)
*   [ ] You name your commits properly [:books:](https://chris.beams.io/posts/git-commit/)
*   [ ] You review PRs carefully and leave your comments [:books:](https://www.pullrequest.com/blog/what-belongs-in-an-effective-code-review-checklist/)
*   [ ] You know how to configure rules in a repository for merging to specific branches (master, develop)

#### [Bitbucket](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#bitbucket)

*   [ ] You know how to reference a Jira ticket in your commit

### [Communication](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#communication)

#### [Slack](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#slack)

*   [ ] You use Slack statuses in line with company policy (remote working, vacationing, in a meeting, etc)

React
-----

*   [ ] You know how to write a function component. [:books:](https://www.robinwieruch.de/react-function-component#react-function-component-example)
*   [ ] You know the difference between function and class components. [:books:](https://medium.com/@Zwenza/functional-vs-class-components-in-react-231e3fbd7108#:~:text=The%20most%20obvious%20one%20difference,which%20returns%20a%20React%20element.)
*   [ ] You know how to define and modify local component's state. [:books:](https://reactjs.org/docs/faq-state.html)
*   [ ] You know what Virtual DOM is and how React uses it to render components. [:books:](https://www.youtube.com/watch?v=RquK3TImY9U)
*   [ ] You know how to use element events and how to incorporate them in React lifecycle [:books:](https://stackoverflow.com/questions/29303456/reactjs-onclick-change-element/29304703#29304703)

### [Hooks](/Technical%20Stack/Mobile%20Developer/React.md#hooks)

*   [ ] You can use <code>useState</code> and <code>useEffect</code> hooks. [:books:](https://www.valentinog.com/blog/hooks/)
*   [ ] You know how hook dependency array works. [:books:](https://medium.com/better-programming/understanding-the-useeffect-dependency-array-2913da504c44)

Application state management
----------------------------

### [Redux](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux)

*   [ ] You can describe full Redux flow [:books:](https://www.youtube.com/watch?v=1w-oQ-i1XB8)

#### [react-redux](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#react-redux)

*   [ ] You know how to apply selector functions to <code>useSelector</code> hook. [:books:](https://levelup.gitconnected.com/react-redux-hooks-useselector-and-usedispatch-f7d8c7f75cdd)
*   [ ] You know how to dispatch actions from React component. [:books:](https://redux.js.org/basics/example)

#### [Redux toolset](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-toolset)

##### [redux-toolkit](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-toolkit)

*   [ ] You know how to create a reducer. [:books:](https://redux-toolkit.js.org/tutorials/basic-tutorial)
*   [ ] You know how to create an action creator [:books:](https://www.johnraptis.dev/redux-toolkit/)

### [Immutable data structures](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#immutable-data-structures)

*   [ ] You understand benefits of using immutable data structures in Redux applications [:books:](https://medium.com/javascript-in-plain-english/why-react-and-redux-need-immutable-data-dae3ab3611a0)
*   [ ] You know how to use at least one of the libraries that provide immutable data structures in redux state [:books:](https://css-tricks.com/using-immer-for-react-state-management/)

#### [immer](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#immer)

*   [ ] You know how to create a reducer that uses immer [:books:](https://hackernoon.com/introducing-immer-immutability-the-easy-way-9d73d8f71cb3)

### [Selectors](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#selectors)

#### [reselect](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#reselect)

*   [ ] You know how to create a selector with <code>createSelector</code> function [:books:](https://medium.com/@pearlmcphee/selectors-react-redux-reselect-9ab984688dd4)

### [Side effects](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#side-effects)

*   [ ] You understand the concept of side effects [:books:](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0#:~:text=A%20side%20effect%20is%20any,the%20parent%20function%20scope%20chain)

#### [redux-saga](/Technical%20Stack/Mobile%20Developer/Application%20state%20management.md#redux-saga)

*   [ ] You know how to take a side effect and dispatch an action based on it [:books:](https://redux-saga.js.org/docs/api/#putaction)
*   [ ] You know how to select data from Redux state using selector functions inside sagas. [:books:](https://redux-saga.js.org/docs/api/#selectselector-args)

HTTP
----

### [Requests](/Technical%20Stack/Mobile%20Developer/HTTP.md#requests)

#### [fetch](/Technical%20Stack/Mobile%20Developer/HTTP.md#fetch)

*   [ ] You know how to create an HTTP request using native <code>fetch</code> [:books:](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
*   [ ] You know how to handle errors returned in HTTP response [:books:](https://levelup.gitconnected.com/the-definite-guide-to-handling-errors-gracefully-in-javascript-58424d9c60e6)

#### [Axios](/Technical%20Stack/Mobile%20Developer/HTTP.md#axios)

*   [ ] You know how to use axios to send HTTP request to an API endpoint [:books:](https://github.com/apptension/cra-template-apptension/blob/master/template/src/modules/users/users.sagas.ts)
*   [ ] You know how to handle errors returned in HTTP response [:books:](https://www.intricatecloud.io/2020/03/how-to-handle-api-errors-in-your-web-app-using-axios/)
*   [ ] You can configure axios to have a predefined base url for making requests

Internationalization
--------------------

### [react-Intl](/Technical%20Stack/Mobile%20Developer/Internationalization.md#react-intl)

*   [ ] You know and use React-intl components [:books:](https://www.newline.co/@dmitryrogozhny/quick-introduction-to-internationalization-in-react-with-react-intl--13b17de9)
*   [ ] You know how to create messages files using defineMessage api [:books:](https://github.com/apptension/cra-template-apptension/blob/master/template/src/routes/home/home.messages.ts)

Date & Time
-----------

*   [ ] You know how to create a Date object for a specific date [:books:](https://www.digitalocean.com/community/tutorials/understanding-date-and-time-in-javascript)

### [date-fns](/Technical%20Stack/Mobile%20Developer/Date%20&%20Time.md#date-fns)

*   [ ] You know how to create a date-fns date object for specific date [:books:](https://date-fns.org/v2.0.0-alpha.7/docs/FP-Guide#usage)
*   [ ] You know how to format and display a date object using standard format strings [:books:](https://www.digitalocean.com/community/tutorials/js-date-fns)

Tools
-----

### [Design](/Technical%20Stack/Mobile%20Developer/Tools.md#design)

#### [Figma](/Technical%20Stack/Mobile%20Developer/Tools.md#figma)

*   [ ] You know how to extract style values (geometry, colours, fonts, etc.) from a design project [:books:](https://www.figma.com/resources/assets/developer-onboarding-guide/)
*   [ ] You know how to extract image assets from a design project
*   [ ] You know how to extract vector icon asset from a project

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