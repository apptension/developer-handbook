Frontend Developer
==================

  

Company practices
-----------------

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

React is an open-source JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

  

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

Apptension React Boilerplate
----------------------------

*   [ ] You know how to initialize a project using Apptension React template of <code>create-react-app</code> generator
*   [ ] You know how to run a linter
*   [ ] You know how to define a new Redux module (Reducer, Saga, Selector)
*   [ ] You know how to create a new route and its component
*   [ ] You understand the difference between <code>src/routes</code> and <code>src/shared/components</code> directories
*   [ ] You can use plop to generate modules and components

Styling
-------

### [CSS](/Technical%20Stack/Frontend%20Developer/Styling.md#css)

*   [ ] You know how to write CSS rules [:books:](https://css-tricks.com/snippets/css/)
*   [ ] You know how to apply basic styles to elements (colour, size, position, etc)
*   [ ] You know how to display and properly scale images [:books:](https://css-tricks.com/aspect-ratio-boxes/)
*   [ ] You know how to center an element horizontally and vertically [:books:](https://css-tricks.com/centering-css-complete-guide/)
*   [ ] You know how to use media queries
*   [ ] You know how to add and use webfonts [:books:](https://css-tricks.com/snippets/css/using-font-face/)

#### [CSS in JS](/Technical%20Stack/Frontend%20Developer/Styling.md#css-in-js)

##### [styled-components](/Technical%20Stack/Frontend%20Developer/Styling.md#styled-components)

*   [ ] You can create a styled component for a primitive element [:books:](https://styled-components.com/docs/basics#getting-started)
*   [ ] You can extend styles of an existing component [:books:](https://styled-components.com/docs/basics#extending-styles)
*   [ ] You can apply global styles [:books:](https://www.robinwieruch.de/react-styled-components)
*   [ ] You can implement media queries [:books:](https://medium.com/@samuelresua/easy-media-queries-in-styled-components-690b78f50053)

#### [Flexbox](/Technical%20Stack/Frontend%20Developer/Styling.md#flexbox)

You can learn how to style HTML elements with flexbox by reading this awesome guide [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

*   [ ] You know how to use column and row layouts [:books:](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Mastering_Wrapping_of_Flex_Items#:~:text=Flexbox%20was%20designed%20as%20a,if%20flex%2Ddirection%20is%20column%20.)
*   [ ] You know how to align children elements [:books:](https://flexboxfroggy.com/)
*   [ ] You know how to stretch child element to the size of its parent [:books:](https://medium.com/@gaurav5430/css-flex-positioning-gotchas-child-expands-to-more-than-the-width-allowed-by-the-parent-799c37428dd6)
*   [ ] You can properly use flex-basis and flex-wrap [:books:](https://css-tricks.com/almanac/properties/f/flex-wrap/)

### [UI Kits](/Technical%20Stack/Frontend%20Developer/Styling.md#ui-kits)

*   [ ] You understand basics of at least one of the UI Kit libraries [:books:](https://material-ui.com/getting-started/installation/)

Date & Time
-----------

*   [ ] You know how to create a Date object for a specific date [:books:](https://www.digitalocean.com/community/tutorials/understanding-date-and-time-in-javascript)

### [date-fns](/Technical%20Stack/Mobile%20Developer/Date%20&%20Time.md#date-fns)

*   [ ] You know how to create a date-fns date object for specific date [:books:](https://date-fns.org/v2.0.0-alpha.7/docs/FP-Guide#usage)
*   [ ] You know how to format and display a date object using standard format strings [:books:](https://www.digitalocean.com/community/tutorials/js-date-fns)

Routing
-------

### [react-router](/Technical%20Stack/Frontend%20Developer/Routing.md#react-router)

*   [ ] You can create a simple route structure using Switch and Route [:books:](https://reacttraining.com/blog/react-router-v5-1/)
*   [ ] You know how to add parameters to a route, and make them required or optional [:books:](https://scotch.io/courses/using-react-router-4/route-params)
*   [ ] You know how to match exactly the route needed [:books:](https://stackoverflow.com/questions/49162311/react-difference-between-route-exact-path-and-route-path)
*   [ ] You know how to render 404 pages [:books:](https://ui.dev/react-router-v4-handling-404-pages/)
*   [ ] You know how to interact with browser history via the history API [:books:](https://reactrouter.com/web/api/history)
*   [ ] You know how to use basic router hooks (useHistory, useLocation, useParams, useRouteMatch) [:books:](https://reactrouter.com/web/api/Hooks)

### [react-router-dom](/Technical%20Stack/Frontend%20Developer/Routing.md#react-router-dom)

*   [ ] You know how to use basic components - Link, NavLink [:books:](https://www.codementor.io/@packt/using-the-link-and-navlink-components-to-navigate-to-a-route-rieqipp42)

Animations
----------

### [CSS Animations](/Technical%20Stack/Frontend%20Developer/Animations.md#css-animations)

*   [ ] You know how write CSS animations - transitions, keyframes [:books:](https://www.youtube.com/watch?v=zHUpx90NerM)

Internationalization
--------------------

### [react-Intl](/Technical%20Stack/Mobile%20Developer/Internationalization.md#react-intl)

*   [ ] You know and use React-intl components [:books:](https://www.newline.co/@dmitryrogozhny/quick-introduction-to-internationalization-in-react-with-react-intl--13b17de9)
*   [ ] You know how to create messages files using defineMessage api [:books:](https://github.com/apptension/cra-template-apptension/blob/master/template/src/routes/home/home.messages.ts)

Development Tools
-----------------

### [Build tools](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#build-tools)

#### [Webpack](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#webpack)

*   [ ] You understand what webpack is used for and what problem it solves [:books:](https://hackernoon.com/webpack-3-quickstarter-configure-webpack-from-scratch-30a6c394038a)
*   [ ] You understand what webpack plugins are and you can add and configure when needed [:books:](https://webpack.js.org/plugins/html-webpack-plugin/#basic-usage)

### [Package managers](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#package-managers)

#### [Yarn](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#yarn)

*   [ ] You're able to use inline commands to add, install & remove packages [:books:](https://devhints.io/yarn)
*   [ ] You understand the benefits of <code>yarn.lock</code> file [:books:](https://www.robertcooper.me/how-yarn-lock-files-work-and-upgrading-dependencies)
*   [ ] You know how to run package.json scripts [:books:](https://classic.yarnpkg.com/en/docs/cli/run/)

#### [NPM](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#npm)

*   [ ] You're able to use inline commands to add, install & remove packages [:books:](https://devhints.io/npm)
*   [ ] You understand the benefits of <code>package-lock.json</code> file [:books:](https://stackoverflow.com/questions/44297803/what-is-the-role-of-the-package-lock-json)
*   [ ] You know how to run package.json scripts [:books:](https://michael-kuehnel.de/tooling/2018/03/22/helpers-and-tips-for-npm-run-scripts.html#:~:text=You%20can%20easily%20run%20scripts,instead%20of%20pointing%20to%20node_modules%2F.)

### [Generators](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#generators)

#### [create-react-app](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#create-react-app)

*   [ ] You can generate a new app using create-react-app cli [:books:](https://create-react-app.dev/docs/getting-started/#creating-an-app)

#### [plop.js](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#plop.js)

*   [ ] You can create components using plop command line tool [:books:](https://blog.logrocket.com/automatically-generate-your-own-react-components-with-plop-js-2da3b39914f3/)

### [React](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#react)

#### [prop-types](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#prop-types)

*   [ ] You know how to describe component's prop types

#### [redux-devtools](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#redux-devtools)

*   [ ] You use <code>redux-devtools</code> to see the current state and play with the state change history [:books:](https://reactjs.org/docs/typechecking-with-proptypes.html)

### [Linters](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#linters)

#### [eslint](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#eslint)

*   [ ] You can run eslint and fix the warnings and errors [:books:](https://eslint.org/docs/user-guide/command-line-interface)

#### [prettier](/Technical%20Stack/Frontend%20Developer/Development%20Tools.md#prettier)

*   [ ] You can run prettier and auto-correct errors [:books:](https://prettier.io/docs/en/cli.html)

Functional programming
----------------------

*   [ ] You know the key concepts of functional programming: pure functions, same input -> same output, no side-effects [:books:](https://thecodeboss.dev/2016/12/core-functional-programming-concepts/)

### [ramda](/Technical%20Stack/Frontend%20Developer/Functional%20programming.md#ramda)

*   [ ] You know how to curry a function [:books:](https://www.educative.io/courses/functional-programming-patterns-with-ramdajs/xV9vlmDPJAE)
*   [ ] You know how to compose a function from other functions
*   [ ] You know how to pipe functions to produce a step by step processing sequence
*   [ ] You can use basic functions such as map, mapValues, find, sort, sortBy, concat, equals, cond, ifElse [:books:](https://randycoulman.com/blog/2016/05/24/thinking-in-ramda-getting-started/)

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

Fonts
-----

*   [ ] You know how to load custom webfonts available in Google Fonts [:books:](https://scotch.io/@micwanyoike/how-to-add-fonts-to-a-react-project#toc-using-hosted-fonts)

Backend & DevOps
----------------

### [DNS](/Technical%20Stack/Frontend%20Developer/Backend%20&%20DevOps.md#dns)

*   [ ] You know what a CNAME record is and when to use it
*   [ ] You know what an A and AAAA records are and when to use them
*   [ ] You know what TXT records is and when to use it
*   [ ] You know how to register a new domain with a chosen DNR
*   [ ] You know how to switch NS from default ones set by DNR to another provider

Tools
-----

### [Design](/Technical%20Stack/Frontend%20Developer/Tools.md#design)

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