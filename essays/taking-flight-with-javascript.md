---
layout: essay
type: essay
title: Taking Flight with JavaScript
# All dates must be YYYY-MM-DD format!
date: 2018-01-19
labels:
  - Software Engineering
  - JavaScript
---

## Hatching the Nest Egg
<img class="ui medium left floated rounded image" src="../images/egg.png">
JavaScript is undoubtedly one of, if not the most ubiquitous programming language in existence today. Indeed, a quick gander at <a href="https://octoverse.github.com/">octoverse</a> reveals it to be the most popular language for open source projects on GitHub by far, with 2.3 million pull requests, more than double that of its closest competitor Python. Within the past decade, new libraries and frameworks catering to JavaScript development have hatched with a fecundity unchecked. Technologies like Ember, Express, Backbone, Angular, Vue, and React among many others, are constantly redefining what it means to write large-scale software systems in the language. Perhaps the most intriguing of such developments has been JavaScript’s incursion into the server side domain, with the advent of Node.js and the Chrome V8 engine. Now a multitude of “full-stack” frameworks exist, allowing developers to roll out web applications developed entirely in JavaScript.

## Leaving the Nest
<img class="ui medium right floated rounded image" src="../images/leave-nest.jpg">
 For me personally, JavaScript has always been that language that I tended to keep my distance from, content to merely gaze upon it from a distance. From the time I first developed an interest in software and programming back in 2010, I was never really drawn to the domain of web development, along with its associated languages and technologies, for reasons that are likely purely based on my previously held naive notions of what it means to write “actual computer programs.” However, that is not to say that I haven’t experience my fair share of JavaScript test flights. With the widespread adoption of HTML5 canvas support by browsers since the publishing of the HMTL5 standard in 2014, I have found myself drawn to this medium from time to time as a way to sketch up small prototype programs in my self guided explorations of cellular automata. I have come to appreciate that JavaScript, along with HTML & CSS, comprises a fairly lightweight framework for hacking together fun little graphical demos that I can then easily share with others, owing to the fact that a JavaScript interpreter is built into every popular web browser in existence today. 

## Spread Those Wings
<img class="ui medium left floated rounded image" src="../images/wings.jpg">
Considering the relatively minute amount of JavaScript coding that I have actually done in my fledgling career as a developer, it is fair to say that I lack the wherewithal to pass too much judgment on the language at this point. As a soi-disant programming language enthusiast, I will say that while I tend to prefer developing large scale systems in languages with strong static typing disciplines, JavaScript possesses many qualities that I find endearing, despite it being both dynamic and weakly typed. JavaScript owes much of its heredity to the Scheme programming language. Brendan Eich, the man who created JavaScript in an astonishingly brief 10 days, had originally intended to embed the Scheme language in the browser, but was later coerced by his superiors at Netscape Communications to create a language aesthetically more aligned with the then rising star, and overly hyped Java programming language. Despite the surface level similarities to Java, the influence of Scheme shines through in many ways in JavaScript’s core design. This is perhaps most clearly exhibited in the language’s treatment of functions as first class entities, allowing for higher-order functions to be composed with little effort. As a fan of functional programming, I find JavaScript’s functional features to be both well designed and a pleasure to use.

```javascript

// Returning a function from a function
// The makeAdder function takes in a number
// closes over its value, and returns a function
// that can then add other numbers to this value
function makeAdder(num) {
	return function(toAdd) {
  	return num + toAdd;
  }
}

let add3 = makeAdder(3);
add3(5) => 8;
```

## A New Nest?
<img class="ui medium right floated rounded image" src="../images/new-nest.jpeg">
I remain on the fence as to whether JavaScript is a suitable language for implementing scalable software systems. I view the lack of compile time type checking as a major handicap. Coupled with often less than helpful error messages, I sense that weak typing could potentially leave larger programs more susceptible to being plagued by cryptic run time errors. On the other hand, JavaScript borrows much from the functional programming school, and is object-oriented enough for me to feel relatively at home while coding in it. While my tendency towards statically typed languages may preclude me from adopting JavaScript as my primary development language longterm, I do see the merits of its ubiquity and robust library support. I look forward to seeing how a framework such as Meteor can awaken the true potential of the language as a medium in which to compose complex software systems. While it is perhaps a stretch to assert that this bird has found his new nesting site, it is certainly safe to say that he will enjoy the flight there. 
