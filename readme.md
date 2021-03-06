![github front end develeper interview questions and answers teaser](https://webman.pro/assets/img/main/webman-front-end-interview-questions-answers-github.jpg)

# Front End Interview Questions and Answers
This information is intended for Front End Developer candidates. The list includes basic theoretical and code questions.  
I hope my experience and the experiences of other developers will help you get better interview results.    

**P.S. My main goal is to help candidates (including myself) get more web knowledge. Let's improve the hard skills of the Front-End community together. Please send you Front-End interview questions via pull request.**

## List of Content
1. [Common interview questions](#common-interview-questions)
1. [Common technical interview questions](#common-technical-interview-questions)
1. [HTML](#html-interview-questions)
1. [CSS](#css-interview-questions)
1. [Javascript](#javascript-interview-questions)
    * [Junior candidate](#junior-candidate)
    * [Middle candidate](#middle-candidate)
    * [Senior candidate](#senior-candidate)
1. [Javascript Coding](#javascript-coding-questions)
1. [React interview questions](#react-interview-questions)
1. [GIT Questions](#git)
1. [Funny Questions](#funny-questions)
1. [Contributing](#contributing)
    * [Answers classification](#answers-classification)
    
## Common interview questions
1. What was the most interesting solution you implemented during your last project? 
1. What is the last book you read?
1. How big was your team?
1. Have you ever worked in [Agile, Scrum or Kanban](https://www.smartsheet.com/agile-vs-scrum-vs-waterfall-vs-kanban) environments?
1. Which developers do you know in the Front End community?
1. What have you heard about the 'Gangs of four'?
1. Explain the difference between unit tests and integration tests? - [@answer--stackoverflow](https://stackoverflow.com/a/5357837/5513804)
1. What are the most common types of web attacks? - [@answer--blog.sucuri.net](https://blog.sucuri.net/2014/11/most-common-attacks-affecting-todays-websites.html)
1. What is 'duck typing'? - [@answer--wikipedia](https://en.wikipedia.org/wiki/Duck_typing)

## Common technical interview questions
1. What is [REST](http://www.restapitutorial.com/)? - [@library--restcookbook](http://restcookbook.com/)
1. What is the difference between PUT and PATCH methods in REST? - [@answer--stackoverflow](https://stackoverflow.com/questions/21660791/what-is-the-main-difference-between-patch-and-put-request)
1. Talk about the differences between [websockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket), long polling and [SSE](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events). - [@answer--stackoverflow](https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet)
1. What is CORS? - [@answer--maxcdn.com](https://www.maxcdn.com/one/visual-glossary/cors/), [@doc--mdn](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
1. List the main things you can do to increase page speed loading? - [@answer--crazyegg.com](https://www.crazyegg.com/blog/speed-up-your-website/)
1. Progressive enhancement vs graceful degradation. What is the difference? - [@answer--w3](https://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement)
1. Do you use [Grunt](https://gruntjs.com/), [Gulp](https://gulpjs.com/), [Webpack](https://webpack.github.io/) or Browserify in your projects?
1. What do you know about "60fps"? How can you achieve it? - [@answer--github](https://github.com/vasanthk/browser-rendering-optimization)
1. What is the difference between layout, painting and compositing? - [@answer--google](https://developers.google.com/web/fundamentals/performance/rendering/?hl=en)

## HTML Interview Questions
1. Could you list major HTML5 tags? - [@doc--mdn](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
1. What does an 'optional' closing tag mean? - [@doc--w3](https://www.w3.org/TR/REC-html40/index/elements.html) 
1. When and how to preload resources? - [@answer--medium](https://medium.com/reloading/preload-prefetch-and-priorities-in-chrome-776165961bbf)
1. What is the difference between id and class?

## CSS Interview Questions
1. What is the difference between 'mobile first' and 'desktop first' - [@answer--codemyviews.com](https://codemyviews.com/blog/mobilefirst )?
1. Which of [these](https://jsfiddle.net/thisman/9o8s2bdk/) selectors has the highest specificity. What color will be applied to the paragraph?
1. What does the pseudo-class `:root` refer to?
1. What preprocessor do you use? ([Sass](http://sass-lang.com/) or [Less](http://lesscss.org/))

## Javascript Interview Questions

#### Junior candidate
1. Who is the author of JavaScript Language?
1. What is the best book for learning JavaScript and why? - [@answer-good-js-books--github](https://github.com/wwwebman/js-books-backpack)
1. What is the type of NaN? How to check if a value is NaN?
1. What the reason that `window.window === window` return true? - [@doc--mdn](https://developer.mozilla.org/pl/docs/Web/API/Window/window)
1. What is the outcome of the JavaScript calculation? `1/0 = ?`

#### Middle candidate
1. What does `this` refer to? - [@answer--javascriptissexy](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
1. What is the JavaScript Event Loop? - [@answer--altitudelabs.com](http://altitudelabs.com/blog/what-is-the-javascript-event-loop/), [@video-Roberts--youtube](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=1244s)
1. What is the Event Delegation? - [@answer--davidwalsh](https://davidwalsh.name/event-delegate), [@code-example](https://jsfiddle.net/thisman/h2eqfsx6/)
1. What is the difference between e.target and e.currentTarget? - [@doc--mdn](https://developer.mozilla.org/en-US/docs/Web/API/Event/currentTarget), [@code-example](https://jsfiddle.net/thisman/gkdeocd6/)
1. What is [`Window.postMessage()`](https://davidwalsh.name/window-postmessage) and where it can be used? - [@doc--mdn](https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage)
1. Is there any difference between Promises and callbacks? Which is better? - [@answer-callback--callbackhell.com](http://callbackhell.com/),  
1. What is recursion? When is the use of recursion useful in Javascript? - [@answer--medium](https://medium.com/@dis_is_patrick/practical-uses-for-recursive-javascript-b8f142552f8b)

#### Senior candidate
1. What patterns do you know and successfully use in JavaScript?
1. What is the difference between Deferred and Promise objects? Where is Deferred object used?
1. What is the problem throttling and debouncing are resolved? What is the core difference between them? - [@answer--medium](https://medium.com/@_jh3y/throttling-and-debouncing-in-javascript-b01cad5c8edf)

## Javascript Coding Questions
* Write a `pipefy` function where a string received is returned, but with the `|` character between each character. Make it possible to execute function in this way: `'javascript'.pipefy()`. - [@code-answer](https://jsfiddle.net/thisman/6ynaf3ot/)
* Write a [currying function](https://medium.com/@adambene/currying-in-javascript-es6-540d2ad09400) that return sum of two numbers.
* Write a [factorial](https://www.mathsisfun.com/numbers/factorial.html) function without [side effect](https://stackoverflow.com/a/8129277/5513804). [@code](https://jsfiddle.net/thisman/8v0h5oLq/)
```js
// Code below must return true
alert(factorial(3) === 6 && factorial(0) === 1);
```
* Which line of the below code will be executed with an error? Why?
```js
10 .toString();
(10).toString();
10..toString();
```
* What is the order of alerts?
```js
setTimeout(function(){
    alert('gorilla');
    setTimeout(function(){
        alert('classical inheritance')
    }, 0);
    alert('drumroll');
}, 0);

alert('banana');
```
* What is the result after code execution: 1, 2 or 3?
```js
var x = 1;
var foo = {
  x:2,
  bar: function() {
    x = 3;
    return this.x;
  }
}
var run = foo.bar;

alert(run());
```

* What below code will return: true or false. What does each part of code return? 
```js
new String('a') instanceof String && 'b' instanceof String;
```

* Does `a({}, 'val')` & `b({}, 'val')` will return the same?
```js
var a = function(obj, val) {
    obj.val = {
        a: 1,
        b: 2,
    }

    return obj;
}


var b = function(obj, val) {
    return obj.val = {
        a: 1,
        b: 2,
    }    
}
```

## React interview questions
1. What happens when you execute `setState()` in the `render()` method?
1. What is the difference between 'smart and dummy' components?
1. How to create higher order component?
1. Tell about React in the SEO context.
1. Why rendering of React Components in the custom `<div id="app">` is good practice than simple to the `<body>`?
1. What does mean "Isomorphic React Application"? - [@answer--smashingmagazine](https://www.smashingmagazine.com/2015/04/react-to-the-future-with-isomorphic-apps/)
1. What is the difference between Mobx & Redux? - [@answer](https://www.robinwieruch.de/redux-mobx-confusion/)

## GIT
1. What is the main difference between `merge` and `rebase`? - [@answer](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

## Funny Questions
1. Do you like parties?
2. Do you know that we have a dress code?

### Contributing
Contributions, questions and comments, pull requests are all welcome.  
**Note**: if you want to change the structure, please open an issue and we will discuss it, but if you have interesting questions or answers, please make pull request.  

Thanks to all these cool people:  
[Ken Hawkins](https://github.com/khawkins98)

#### Answers classification
 **@answer-[tag]--[source tag]** - General Theoretical Answer.   
 **@doc-[tag]--[source tag]** - Documentation  
 **@library-[tag]--[source tag]** - More Complex Answer  
 **@code-[tag]** - Code Example from jsfiddle || codepen || jsbin  
 **@practice-[tag]--[source tag]** - Good Practices  
 **@video-[tag]--[source tag]** - Video Materials
