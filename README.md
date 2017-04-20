# Redux and Thunk in React

Implementation of [A Dummy’s Guide to Redux and Thunk in React codelab](https://medium.com/@stowball/a-dummys-guide-to-redux-and-thunk-in-react-d8904a7005d3), a very simple tutorial for the first steps in Redux and Thunk.

## How to Setup

First you need:

* [Node.js with npm](https://nodejs.org/en/)

After you clone this code, select the project folder in the command line and:

```
$ npm install
$ npm start
```

After this, you can see the code working in your [local host](http://localhost:3000) (http://localhost:3000).
It's a very simple example, that just load a list from this [site](http://5826ed963900d612000138bd.mockapi.io/items) and show a loading, an error or the list messages, for each possible stage.

You can see the error message changing the this url in `src/components/ItemList.js` and restarting the project:
```
this.props.fetchData('http://5826ed963900d612000138bd.mockapi.io/items');
```


## Built with

* [WebStorm 2017.1.1](https://www.jetbrains.com/webstorm/)

## Also see

* [Sample Code](https://github.com/stowball/dummys-guide-to-redux-and-thunk-react)