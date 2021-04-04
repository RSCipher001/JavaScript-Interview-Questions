# JavaScript-Interview-Questions
A list of good interview questions for JavaScript candidate.

JavaScript
----------
- What are the differences between arrow function and regular function?
- What is a callback function? Explain with an example
- How to convert a callback function into a promise?
- Can we call a function with callback as well as a promise? If yes, how?
- What are the differences between `__proto__` and prototype?
- What is constructor function in javascript?
- What do you understand by object reference?
- How to shallow copy an object?
- How to deep copy an object?
- What is the use of `Object.assign` method?
- What is the use of `Object.create` method?

- Call vs bind vs apply?
- What are common ES6 methods for working with arrays?
    - find
    - filter
    - map
    - forEach
    - some
- What is a `Promise`.
- What is the use of `async/await` keyword?
- How to run first 3 statements in parallel?
```js
const user = await User.findOne({ _id: userId });
const organization = await Organization.findOne({ _id: organizationId });
const callRates = await fetchCallRates(count);

conts response = await doSomething(user, organization, callRates);
```

Node
----
- What is the difference betwen `import` and `require` when importing modules?
- What are streams in nodejs?
- How to clear require cache?


HTML 5
------
- What is intersection observer?
- What is a service worker?
- What is mutation observer?
- What is localStorage?
- What is sessionStorage?
