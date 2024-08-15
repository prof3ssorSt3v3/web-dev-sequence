# JavaScript Development Topics

This is a sequence for learning JS topics. It is not an absolute list of all topics, nor is it a mandatory order that you must use to learn JS. It is just a logical sequencing of some of the more
important topics and features of the language.

1. Variables

- using `let` and `const`
- declaring variables
- assigning values to variables
- the purpose of variables
- replacing `var` with `let` and `const`
- naming rules

2. DataTypes

- JS primitives
- JS Objects
- single quotes, double quotes, backticks
- `typeof` operator

3. Truthy vs Falsey

- the list of falsey values
- concept of `nullish`
- `null` vs `undefined`

4. Logical Operations

- `if` statement
- `else if` and `else`
- compound if statements with `&&` and `||`
- comparison operators <, >, !, !=, !==, <=, >=, ==, ===
- nullish coalescing operator
- ternary operators
- logical short circuiting
- `switch case` statements

5. Functions

- purpose of functions
- function declarations vs expressions
- return statements
- parameters
- arrow functions vs regular functions
- default values

6. Scope and Execution Context

- global vs local scope
- block scope
- execution contexts
- hoisting
- JS memory stack vs heap

7. String Methods

- String object vs string primitive
- string concatenation
- variable and expression interpolation in template strings
- String methods
- length property
- square brackets to access characters

8. Number Methods

- integer vs floating point numbers
- NaN
- parseInt and parseFloat
- toString(base)

9. Math Object

- round, floor, ceil
- random numbers
- random colours
- operators +, -, \*, /, %

10. Operator Precedence
11. Objects

- dot notation vs square bracket syntax
- object literals
- adding, editing, deleting properties
- checking for existence of properties
- destructive vs copying methods

12. Arrays

- purpose of arrays
- push, pop, shift, unshift, length
- slice, splice
- forEach, map, filter, reduce
- find, findIndex, findLast
- concat
- every, fill, some
- sort vs toSorted
- reverse vs toReversed
- join & String.split

13. Loops

- for()
- for( in )
- for( of )
- while()
- do..while()
- iterable vs enumerable

14. Date Objects

- Date Objects
- Temporal Objects

14. Namespaces

- limiting global scope variables
- calling namespace functions from within namespaces

15. Modules and Imports

- export
- export default
- import and default import
- dynamic import()
- import for side-effects

16. Destructuring, spread, rest
17. Core JS, Web APIS, and NodeJS
18. `<script>` tags

- async
- defer
- type

19. The DOM

- How JavaScript sees the HTML
- window
- document
- document.body

20. Nodes and Elements

- difference between Nodes and Elements
- text nodes
- elements
- documentFragments
- children, childNodes, firstChild, firstElementChild, nextSibling, previousSibling, nextElementSibling...
- createElement
- createDocumentFragment
- innerHTML, textContent, outerHTML

21. Traversing, Appending, Finding, Removing Nodes

- querySelector
- querySelectorAll
- getElementById
- getElementsByClassName
- getElementsByTagName
- appendChild, append
- removeChild, remove

22. Attributes

- attributes vs properties
- getAttribute
- setAttribute
- dataset properties

23. Generating HTML from Data

- Element.innerHTML = Array.map( ).join("")
- templates
- template.content.cloneNode(true)
- Not calling append inside a loop

24. Events

- mouse events
- keyboard events
- window events: resize, scroll
- onLine, offLine
- touch events
- pointer events
- form events
- bubbling and capture phase
- preventDefault
- stopPropagation
- addEventListener, removeEventListener
- options {once: true}
- page lifecycle events: DOMContentLoaded, load, unload, beforeunload, pageshow, pagehide
- onclick old 1990s event approach

25. Errors and Exceptions

- try..catch()
- built-in error types
- new Error()

26. Deep vs Shallow Copy and StructuredClone
27. Form Validation

- submit vs requestSubmit
- checkValidity, reportValidity
- invalid event, submit event
- form properties and encoding

28. Callback functions
29. Promises
30. XML, Yaml, Txt formats
31. JSON format
32. JS Objects vs JSON
33. fetch and XMLHttpRequest

- APIs vs Web APIs (HTML5)
- HTTP Methods
- HTTP Status codes
- Request Objects
- Response Objects
- Headers
- Caching
- Body
- Blobs
- Files
- FormData
- Uploading files and data
- XMLHttpRequest

34. APIs

- What is an API
- API keys
- keys and params through querystring, headers, body
- https://random-data-api.com/documentation - v2
- https://jsonplaceholder.typicode.com
- https://dummyjson.com/
- reddit api
- github api
- openweather api
- theMovieDataBase api
- https://picsum.photos
- unsplash API
- pexels API
- other example apis

35. Form Validation
36. Regular Expressions
37. Bitwise operations

- AND, OR, XOR, NOT
- odd, even

38. Maps and Sets
39. WeakSet, WeakMap, WeakRef
40. Symbols
41. Generators and Iterators

- generator
- yield
- iterators

42. setTimeout, setInterval

- set and clear timers

43. Tasks, Microtasks, requestAnimationFrame, JS Event Loop
44. Higher Order and Pure Functions
45. Execution context and closures
46. `===` vs `==` vs `Object.is` equality
47. Prototypes

- prototype objects
- prototype chain
- **proto** - from objects
- .prototype - from functions
- .constructor
- Object.create
- Object.assign
- Object.hasOwn
- Object.freeze()
- Object.seal()
- property descriptors
- Object.defineProperties
- Object.defineProperty

48. `new` and `this` and lexical scope
49. call, apply, and bind
50. Class keyword

- constructor()
- extends
- this
- private and public methods and members
- static methods
- extending errors

51. Client-Side Storage

- cookies
- localStorage
- sessionStorage
- Cache API
- IndexedDB
- Files

52. Single Source of Truth
53. State management
54. Audio and Video
55. HTML5 Canvas
56. Web Components
57. Service Workers
58. Messaging
59. PWA

- manifest files
- service workers
- caching strategies
- WorkBox

60. Web Workers
61. Worklets
62. Shared Workers
63. WebAuth
64. OAuth
65. History API
66. Navigation API
67. Web Animations API
68. CSSOM
69. Notifications API
70. Sensor APIs
71. Screen Wake Lock API
72. Observers: Resize and Mutation and Intersection
73. Geolocation API
74. Page Visibility API
75. ScreenOrientation API
76. DeviceOrientation API
77. Drag and Drop API
78. Permissions API
79. Web Payments API
80. Clipboard API
81. View Transitions API
82. FullScreen API
83. Testing

- Mocha
- Chai
- Jest
- Vitest

84. JAMStack
85. SPA vs MPA
86. Build Tools and Packagers

- Webpack
- Parcel
- Vite

87. Babel
88. Understanding Why to Use a Framework
89. React
90. NextJS
91. Svelte
92. Gatsby
93. VueJS
94. FireBase

- FireStore
- Hosting
- Functions
- Storage
- Authentication
- Messaging

95. Prioritized Task Scheduling
96. Selection API
97. Streams
98. ByteArrays
99. WebSockets and Socket.io
100.  WebRTC
101.  Audio Context API
102.  Web Speech API
103.  Web Share API
104.  Web Push API
105.  Web Crypto API
106.  WebGL
107.  WebXR
108.  Wasm
