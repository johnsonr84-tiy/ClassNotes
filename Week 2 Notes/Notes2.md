# __Week 2 Notes & Journal__

## Weekly Forecast
- ECMA script
 - [Cross browser support]([kangax.github.io/compat-table/es6).
 - know your baseline browsers
- Codewars
- MDN
- Flexbox
- Javascript cross browser support
- MDN - JavaScript Guide Introduction

##### General Tips
- For _links_, document the link and how you got to it.
- __!mdn alert__ - means a search in google only on 'mdn'
- Firefox
- about: blank - goes to new tab
- meaning of HACK
  - MIT: doing high level pranks
  - making computers do what they don't normally do

##### Shortcuts
- Atom: type `log` and `tab` and it will create `console.log();`
- $0 in console in browser bring in the highlighted node
- press `esc` to open up "filter" in Chrome after _inspect_


##### Codewars.com Tips
- Library - choose filter

# Monday
 - Learning how to be presice in the instructions programmed using JS.
 - using MDN to learn Javascript
 #### - HW | JS-Intro
  - fork gist
  - click raw
  - past to scratch pad
  - save as
  - work locally
  - got to line
  - command R - run code
    - not show up if passed
    - show up if failed
  - pair program
  - Make through part 4

## Show how to use prompt
  - Under available toolbox buttons, click __scratch pad__.
  -

# Tuesday
- Go through
- Document notes/questions
- Excersize one
  0. index.html page with `script` tags
  1. to test, write `console.log('');`
  2. open index in broser
  3. open inspect
  4. open console
  5. refresh
  6. should show `console.log` text
  7. __NOTE__ CANNOT DO:
    - REFERENCE script file in script tag and put JS between script tag
- analyze nodes in DOM tree
 - looking at properties and things that work with each node
 ###### Firefox
 0. go to console in browser
 1. highlight node
 2. type $0 in console
 3. click on the node `p` to get "Filter properties" to pop up
  - properties on node
  - methods/functions
    - if functions on an object then it's called a method...
  - in filter properties

#### Chrome : better for inspecting JS
- element selector
- click _Event Listeners_
- 3 ways to in
 - (embedded) script in html page
 - __external file__ *** best way
 - inline (rarely use)
  - frame works do this for you though
- order matters
 - put script tag at bottom
  - the way things are loading...
   - the html needs to load then the html

### More Tuesday: Variables, Functions, ES6
- `var`, `let` can reassign
- can't change `const` variable reassign
- define `const` and `let` before you can `console.log`
- `var` can be logged though not defined, nothing in it, and will log an `undefined`
- Python Tutor [example]([[Cross browser support]([https://goo.gl/I47LV6]).


four ways to run function
- function declaration
- function expression
- when assign function to variable, that's a `functione expression`
- fat arrow `=>`


## JS:
### Monday
- window.prompt("What's your name?");
- window.alert("Hello");
- 3 ways to tap into DOM
 - element (lowest on specificity)
 - id (most specific)
 - class (reusable)
- Query Selector
- __document.querySelector__
 - start at top of the DOM
 - whole index.html file
  - assign --- node <main>
  - document.querySelectorAll
  - `element.querySelector()`
  - chooses first node
  - element.querySelectorALL()
    - get back NodeList

- div.user-panel.main input[name=login]
- console.assert(1 == "1");
- console.assert(1 === "1");
  - No feedback with "console.assert();" is a good thing.
  - good to use for testing (scratchpad, firefox, refresh page)

### Tuesday

## HTML
- `<input>`
  - types
  - properties
  - inputs commonly with forms
  - `<form>`
   - `event.preventDefault();`
    - part of a function after `.addEventListener("click")`
      - <script>`
        document.querySelector("#id-checkbox").addEventListener("click", function(event){
            alert("preventDefault will stop you checked this checkbox!")
            event.preventDefault();
        }, false);`
    </script>




- CSS





## Interview - Certain Problem to Show Up
- The solution will only solve part of it problem

## Markdown Syntax

This is a link to [github](https://github.com).



# Keyboard Shortcuts

`⌘\` toggle nav-tree in Atom

`ctrl-shift-m` show markdown preview

# Markdown

## level 2 heading
### level 3 heading
#### level 4 heading
##### level 5 heading
###### level 6 heading

Alt Heading Type
================


level 2 alt
-----------

Inline `code`

- `$` - command line (CLI) prompt
- `>` - repl prompt
- `//` - single line JS Comment
-

2. ordered list
1. where the actual
0. numbers don't matter
