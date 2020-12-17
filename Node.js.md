
**Nodejs**
* JavaScript runtime built on Chrome's V8 JavaScript engine.
* we can use nodejs for bundling our website code packages.
* a **callback** a function that node will callback later in a program that is done with help of asynchronous programming use example of starbucks or any order for ex hotel orders.
* REPL stands for read, eval,print,loop
* .help for getting help in REPL session
* In **Nodejs shell** if you double tab the `tab` key then list of the keywords will be shown  and if for `crypto you type cr` then single tab then crypto will be auto completed.
* simple code 
```js
const http = require('http');

const server = http.createServer((req, res) => {
  res.end('Hello World\n');
});

server.listen(4242, () => {
  console.log('Server is running...');
});
```
* setTimeout is used to delay the messages or service of any application.
```js 
setTimeout(
  () => {
    console.log('Hello after 4 seconds');
  },
  4 * 1000
);



const rocks = who => {
  console.log(who + ' rocks');
};

setTimeout(rocks, 2 * 1000, 'Pluralsight');

```
* challenge 
```js
const theOneFunc = delay => {
  console.log('Hello after ' + delay + ' seconds');
};

setTimeout(theOneFunc, 4 * 1000, 4);

setTimeout(theOneFunc, 8 * 1000, 8);
```
* setInterval is used repeat same thing again and again 
```js
setInterval(
  () => console.log('Hello every 3 seconds'),
  3000
);

```



