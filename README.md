# curly-octo-barnacle
[Indrek Lasn] Let's Build: Cryptocurrency Native Mobile App With React Native + Redux

Grab the article at [https://medium.com/react-native-training/bitcoin-ripple-ethereum-price-checker-with-react-native-redux-e9d076037092](https://medium.com/react-native-training/bitcoin-ripple-ethereum-price-checker-with-react-native-redux-e9d076037092)

## Tips

* I had difficulties on running the Expo emulator on my handset - Nokia 6.1 - directly through the command-line/QR-code combination; after toying-around with some ipconfig/Firewall bits'n'pieces I eventually made my life a little easier through letting Expo do all the hard graft for me - by installing [Local Development Tool: XDE](https://docs.expo.io/versions/latest/introduction/installation.html) (direct Windows [link](https://xde-updates.exponentjs.com/download/win32))
* [es6 decontructing](https://www.google.ch/search?q=es6+decontructing&oq=es6+decontructing&aqs=chrome..69i57j0.4577j0j7&sourceid=chrome&ie=UTF-8)
* [HTMLElement.style](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/style)
* [Learn how to build an Astronomy Picture of the Day App with the NASA API and React + Redux (Part II)](https://medium.freecodecamp.org/learn-how-to-build-astronomy-picture-of-the-day-app-with-nasa-api-and-react-redux-part-ii-83f15970d0e3)
* Redux debugging middleware, allows us to use the Redux Chrome Devtools in Remote mode: [redux](https://www.npmjs.com/package/redux) — Redux library [react-redux](https://www.npmjs.com/package/react-redux) — Glue for React and Redux, "remote-redux-devtool remotedev-rn-debugger"
* [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en)
* [redux-thunk](https://www.npmjs.com/package/redux-thunk) — Redux thunk lets us to return a function inside an action instead returning a object)
* redux-logger — logs the previous state, action and the next state in the console (logger must be the last middleware in chain, otherwise it will log thunk and promise, not actual actions [(#20)](https://github.com/evgenyrodionov/redux-logger/issues/20))
* [redux-promise](https://www.npmjs.com/package/redux-promise) — Allows us to resolve async actions (promises) with Redux. Example: Fetching data from an API
* import [Platform](https://facebook.github.io/react-native/docs/platform-specific-code.html#platform-module) from 'react-native'
* createStore() [accepts the following arguments](https://github.com/reactjs/redux/blob/master/docs/api/createStore.md): reducer, preloaded state, enhancer
* Redux [store enhancers](https://github.com/reactjs/redux/blob/master/docs/Glossary.md#store-enhancer) ([More information](https://github.com/reactjs/redux/blob/master/docs/api/compose.md))
* [even more information](https://github.com/reactjs/redux/blob/master/docs/api)...

## What's it all about?

* <Text> Text is JSX - a syntax for embedding XML within JavaScript. Many frameworks use a special templating language which lets you embed code inside markup language. In React, this is reversed. JSX lets you write your markup language inside code. It looks like HTML on the web, except instead of web things like <div> or <span>, you use React components. In this case, <Text> is a built-in component that just displays some text. TL;DR A React component for displaying text.
* <View> The most fundamental component for building a UI, View is a container that supports layout with [flexbox](https://facebook.github.io/react-native/docs/flexbox.html), [style](https://facebook.github.io/react-native/docs/style.html), [some touch handling](https://facebook.github.io/react-native/docs/handling-touches.html), and [accessibility](https://facebook.github.io/react-native/docs/accessibility.html) controls. View maps directly to the native view equivalent on whatever platform React Native is running on, whether that is a UIView, <div>, android.view, etc. View is designed to be nested inside other views and can have 0 to many children of any type. This example creates a View that wraps two colored boxes and a text component in a row with padding.
* StyleSheet: A StyleSheet is an abstraction similar to CSS StyleSheets. Creates a new StyleSheet. Styling for RN is flex-box based. [Uses the Yoga layout engine](https://facebook.github.io/yoga/). We pass styles to elements trough the style prop. Not too comfortable with flexbox? No worries, [here are the best resources to master flexbox!](https://medium.com/@wesharehoodies/master-flexbox-with-these-3-fantastic-courses-for-free-432b1fcd4361)

## Thanks

Thanks goes out to Indrek Lasn for the FREE stuff!

* [Indrek Lasn Medium](https://codeburst.io/@wesharehoodies) ...Author, software engineer, founder...
