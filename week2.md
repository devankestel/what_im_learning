## Saturday

* [x] [Ducks: Redux Reducer Bundles](https://github.com/erikras/ducks-modular-redux) | `* * * *`
  * I'm considering using this pattern for my next React/Redux app. Seems like the flow of the app will be easier to follow, but ducks could potentially lead to longer files than desired. Documentation was concise and clear.
* [x] [GA React Todo Tutorial Repo](https://github.com/goopscoop/ga-react-tutorial/tree/6-reduxActionsAndReducers) | `* * * * *`
  * Uses the redux-duck pattern (even though there is only one duck needed for TODO) to create TODO App along with webpack, react-router, containers/components pattern, ES6, etc. Basically, about as full of best practices as you are going to get.
* [x] [Redux Docs: Writing Tests](http://redux.js.org/docs/recipes/WritingTests.html) | `* * * *`
  * Official guide for writing unit tests in Redux using Jest and Enzyme. Goes over actions, reducers, middleware, components.

## Sunday

* [x] [Javascript Testing Framework Comparison: Jasmine vs. Mocha](https://www.codementor.io/javascript/tutorial/javascript-testing-framework-comparison-jasmine-vs-mocha) | `* * * * *`
  * Best article I found that concisely explains the different capabilities of the two most popular JS testing frameworks and what additional libraries are needed. The way it was written, it was easy to compare features with what I'm used to with RSpec for server side tests.
* [x] [So You Want to be a Functional Programmer (Part 1)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536#.li48cfrsx) | `* * * *`
  * No new information here, but an entertaining introduction to the series. I think I'm going to enjoy the direct JS/Elm comparisons as the series delves into more complex functional concepts.
* [x] [So You Want to be a Functional Programmer (Part 2)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-2-7005682cec4a#.hsj35e65j) | `* * * *`
  * Again, nothing new, but the review on JS closures was nice and used an identical example from YDKJS. Onward to Part 3!
* [x] [So You Want to be a Functional Programmer (Part 3)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-3-1b0fd14eb1a7#.mxfm25nf1) | `* * * *`
  * Finally, some new material! Had heard the term "point free notation" here and there but didn't have the occasion to look it up. Awesome that functional languages can do this; I would think this would be harder in an OO language where functions that take in zero parameters are much more commonplace.
* [x] [So You Want to be a Functional Programmer (Part 4)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-4-18fbe3ea9e49#.2gc05m6g9) | `* * * * *`
  * Best intro to currying I have seen so far. Definitely made me start realizing that I need to place more emphasis on how I order my parameters so that I can take advantage of currying more often. Decent review of map, filter, reduce defined iteratively in JS.
* [x] [So You Want to be a Functional Programmer (Part 5)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-5-c70adc9cf56a#.upvenvyzj) | `* * *`
  * This article provided a concrete picture of how functional languages achieve operations in parallel by design of the language alone. The explanation on types also clarified some nuance I had failed to see in my previous work with Elm, but I do not think it would serve as a clear explanation for a total beginner to Elm.
* [x] [So You Want to be a Functional Programmer (Part 6)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-6-db502830403#.cxq9njehs) | `* * * *`
  * Nice to have an intro to Ramda, something I've been wanting to look at but had not gotten the chance yet. Didn't need the sales pitch on Elm as I'm already sold. All in all a nice series that I would recommend to friends just getting into FP.

## Monday
  * [x] [Getting Started with Rails and GraphQL](http://mgiroux.me/2015/getting-started-with-rails-graphql-relay/) | `* * * * *`
    * GraphQL is a term I had heard thrown around for a while, but didn't really understand much about until reading this post. As someone with a Rails background, this was the right lens for introducing myself to the API.
  * [x] [YDKJS: *this* & Object Prototypes CH1: `this` Or That?](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch1.md) | `* * * *`
    * Explanation of how `this` differs from lexical scope and cannot be treated as such. Reminder: lexical scope = author time and `this` = runtime.
  * [x] [YDKJS: *this* & Object Prototypes CH2: `this` All Makes Sense Now!](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch2.md) | `* *`
    * The first part of YDKJS that has felt like it went from 0 to 100 without the proper ramp up. Certainly all of the information is there, but the chapter is the longest so far in the series and could have been broken down more effectively. One would have to read this several times to absorb all the information successfully. That said, I'm sure it works well as a reference when coding.

## Tuesday

  * [x] [Functional Programming in Haskell by University of Glasgow: Week 3](https://www.futurelearn.com/courses/functional-programming-haskell/) | `* * * * *`
    * This course continues to expand my understanding of functional concepts. Week 3 went deeper into recursion as well as introduced custom data types and binary trees.
  * [x] [Trees in Haskell](https://dkalemis.wordpress.com/2014/01/23/trees-in-haskell/) | `* * * * *`
    * Commenters from the Glasgow Haskell course recommended this intro to binary trees as supplemental reading. I'm not sure if there was any added clarity when compared with the official material, but the repetition helped solidify trees in my mind.

## Wednesday

  * [x] [Functional Programming in Haskell by University of Glasgow: Week 4](https://www.futurelearn.com/courses/functional-programming-haskell/) | `* * * * *`
    * This week covered a wide range of topics, as the general subject was "complex programs." Of particular interest, parsers in Haskell would probably be good for converting text to PDF, MSWord and other formats, as the code for doing similar conversions to XML and JSON proved both elegant and powerful. It also reinforced the general topics of parsing and lexing, which were introduced to me in YDKJS, even though I am now learning them in a different language. QuickCheck is an efficient and simple way of getting testing done for programs that are experimental. Ordinarily, I forego writing tests entirely for experimental code, and it's nice to know there is an alternative that lies between zero tests and implementing a full suite of unit tests. Finally, I enjoyed the interview with Graham Hutton. His description of his students who are taught from year one to think in a functional paradigm, rather than OO, left me a tiny bit jealous. I am putting his book, [Programming in Haskell](http://www.cs.nott.ac.uk/~pszgmh/pih.html) on my short list for Haskell learning materials to peruse in the near future.

## Thursday

  * [x] [Functional Programming in Haskell by University of Glasgow: Week 5](https://www.futurelearn.com/courses/functional-programming-haskell/) | `* * * *`
    * The information on infinite data structures is valuable and eye opening. This is where lazy evaluation truly shines. The types chapter seems oddly tacked on, and though good info, doesn't really seem to fit the flow of the course. 
