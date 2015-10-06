# JavaScript: The Esoteric Parts

## Table of Contents

- Introduction
- Classical vs. Prototypal inheritance
- The `new` and `this` keywords
- The ES6 `class`
- Semicolons
- Tabs vs Spaces
- Semantic Versioning
- Observer Patterns
- Frameworks vs. Vanilla
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## Introduction

## Classical vs. Prototypal inheritance

JavaScript uses prototypal inheritance instead of classical inheritance.  Knowing the difference is key to understanding the discussions below.

- [Classical Inheritance in JavaScript](http://www.crockford.com/javascript/inheritance.html)
- [Why Prototypal Inheritance Matters](http://aaditmshah.github.io/why-prototypal-inheritance-matters/)
- [Benefits of prototypal inheritance over classical?](http://stackoverflow.com/questions/2800964/benefits-of-prototypal-inheritance-over-classical)

## The `new` and `this` keywords

Controversy over how to do class-like inheritance in JavaScript existed long before the ES6 `class` keyword.

- [Crockford on JavaScript](https://www.youtube.com/watch?v=ya4UHuXNygM&t=50m23s)

## The ES6 `class`

ES6 introduced the `class` keyword.  ES6 classes are syntactical sugar over prototypal inheritance.  There are many arguments for and against the `class` keyword in JavaScript.

- [How to Fix the ES6 `class` keyword](https://medium.com/javascript-scene/how-to-fix-the-es6-class-keyword-2d42bb3f4caf) by Eric Elliott
- [The Two Pillars of JavaScript](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3) by Eric Elliott
  - [Crockford's Wager](https://medium.com/@hypercubed/ok-let-me-play-devils-advocate-for-a-second-and-introduce-crockford-s-wager-f8e051cc52a) comment by Jayson Harshbarger
- [Not Awesome: ES6 Classes](https://github.com/joshburgess/not-awesome-es6-classes) by joshburgess
  - [comment](https://www.reddit.com/r/javascript/comments/3nkycz/not_awesome_es6_classes_a_curated_list_of/) by rauschma

## Semicolons

JavaScript has a feature called Automatic semicolon insertion (ASI).  With ASI, you are able to omit certain semicolons.  Use of this feature is controversial.  After the `class` keyword, ASI may be JavaScript's most controversial syntactic feature.

- [An Open Letter to JavaScript Leaders Regarding Semicolons](http://blog.izs.me/post/2353458699/an-open-letter-to-javascript-leaders-regarding) by Isaac Z. Schlueter
- [JavaScript Semicolon Insertion, Everything you need to know](http://inimino.org/~inimino/blog/javascript_semicolons)
- [Understanding automatic semi-colon insertion in JavaScript](http://jamesallardice.com/understanding-automatic-semi-colon-insertion-in-javascript/)

## Semantic Versioning

Semantic Versioning, while not a feature of JavaScript, is vital to JavaScript package management and is often misunderstood.

- [We fail to follow SemVer – and why it needn’t matter](https://www.youtube.com/watch?v=tc2UgG5L7WM&index=6&list=PLFZ5NyC0xHDaaTy6tY9p0C0jd_rRRl5Zm) by Stephan Bönnemann at JSConf Budapest 2015
- [Semantic Versioning: Why You Should Be Using it](http://www.sitepoint.com/semantic-versioning-why-you-should-using/)

## Observer Patterns

- [Comparison between different Observer Pattern implementations](https://github.com/millermedeiros/js-signals/wiki/Comparison-between-different-Observer-Pattern-implementations)

# Contribution Guidelines

Please read the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Titles should be [capitalized](http://grammar.yourdictionary.com/capitalization/rules-for-capitalization-in-titles.html).
- Use the following format: `[Content Title](content link)` and `by Author Name` where appropriate.
- Choose corresponding section (and subsection) for your suggestion. 
- New sections (and subsection) are welcome.
- Try to keep this resource objective but feel free to link to your subjective resource.
- Try to link to primary sources instead of collections.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
