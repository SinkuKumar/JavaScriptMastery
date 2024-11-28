### **1. Hello World in the Console**
**Goal:** Practice using the console and basic JavaScript syntax.

- Write a script that logs "Hello, World!" to the console.
- Modify it to log your name instead of "World".

**Hints:**
```javascript
console.log("Hello, World!");
```

---

### **2. Basic Variables**
**Goal:** Learn about variables and string concatenation.

- Create two variables: `firstName` and `lastName`.
- Log a message like "My name is John Doe" using these variables.

**Hints:**
```javascript
let firstName = "John";
let lastName = "Doe";
console.log("My name is " + firstName + " " + lastName);
```

---

### **3. Simple Calculator**
**Goal:** Practice basic arithmetic and input/output.

- Write a function that takes two numbers as arguments and returns their sum.
- Test your function with different inputs.

**Hints:**
```javascript
function add(a, b) {
  return a + b;
}
console.log(add(3, 5)); // Example usage
```

---

### **4. Odd or Even**
**Goal:** Learn conditionals and the modulo operator.

- Write a function `isEven` that checks if a number is even.
- If the number is even, return `true`; otherwise, return `false`.

**Hints:**
```javascript
function isEven(num) {
  return num % 2 === 0;
}
console.log(isEven(4)); // true
console.log(isEven(7)); // false
```

---

### **5. Array Basics**
**Goal:** Get comfortable working with arrays.

- Create an array of five of your favorite movies.
- Write code to:
  1. Add a new movie to the array.
  2. Remove the first movie from the array.
  3. Log the updated array.

**Hints:**
```javascript
let movies = ["Inception", "Interstellar", "Avatar", "Matrix", "Titanic"];
movies.push("The Dark Knight");
movies.shift();
console.log(movies);
```

---

### **6. Looping Through Numbers**
**Goal:** Practice loops and iteration.

- Write a loop that logs the numbers from 1 to 10.
- Modify it to log only even numbers.

**Hints:**
```javascript
for (let i = 1; i <= 10; i++) {
  if (i % 2 === 0) {
    console.log(i);
  }
}
```

---

### **7. Build a Simple Object**
**Goal:** Understand objects and their properties.

- Create an object representing a book with `title`, `author`, and `pages`.
- Write a function `describeBook` that takes the object and logs a description like: "Title by Author, Pages pages."

**Hints:**
```javascript
let book = {
  title: "1984",
  author: "George Orwell",
  pages: 328
};

function describeBook(book) {
  console.log(`${book.title} by ${book.author}, ${book.pages} pages.`);
}
describeBook(book);
```

---

### **8. Countdown Timer**
**Goal:** Practice setInterval and timing functions.

- Create a function `countdown` that counts down from 10 to 0.
- Log each number every second.

**Hints:**
```javascript
function countdown() {
  let num = 10;
  let timer = setInterval(() => {
    console.log(num);
    num--;
    if (num < 0) clearInterval(timer);
  }, 1000);
}
countdown();
```

---

### **9. Guess the Number**
**Goal:** Combine conditionals, loops, and random numbers.

- Write a script that generates a random number between 1 and 10.
- Allow the user to guess the number (using `prompt`).
- Log whether the guess was correct or not.

**Hints:**
```javascript
let randomNumber = Math.floor(Math.random() * 10) + 1;
let guess = parseInt(prompt("Guess a number between 1 and 10:"));
if (guess === randomNumber) {
  console.log("Correct!");
} else {
  console.log(`Wrong! The number was ${randomNumber}.`);
}
```

---

### **10. Palindrome Checker**
**Goal:** Practice string manipulation.

- Write a function `isPalindrome` that checks if a string is a palindrome (reads the same backward as forward).
- Test it with words like "racecar" and "hello".

**Hints:**
```javascript
function isPalindrome(str) {
  let reversed = str.split('').reverse().join('');
  return str === reversed;
}
console.log(isPalindrome("racecar")); // true
console.log(isPalindrome("hello")); // false
```

---

Here’s a **set of 40 additional JavaScript exercises**, building on the previous 10. These range from intermediate to more advanced tasks, covering various JavaScript concepts:

---

### **Intermediate-Level Exercises**

#### **11. FizzBuzz**
Write a program that prints numbers from 1 to 100:
- For multiples of 3, print "Fizz".
- For multiples of 5, print "Buzz".
- For multiples of both, print "FizzBuzz".

---

#### **12. Find the Largest Number**
Create a function `findLargest` that takes an array of numbers and returns the largest one.

---

#### **13. Reverse a String**
Write a function `reverseString` that reverses a given string.

---

#### **14. Factorial Calculator**
Write a function `factorial` that calculates the factorial of a number (e.g., `factorial(5) = 120`).

---

#### **15. Sum of an Array**
Write a function `sumArray` that calculates the sum of all elements in an array.

---

#### **16. Count Vowels**
Write a function `countVowels` that counts the number of vowels in a given string.

---

#### **17. Remove Duplicates**
Write a function `removeDuplicates` that removes duplicate values from an array.

---

#### **18. Random Quote Generator**
Create an array of quotes and write a function `getRandomQuote` that returns a random one.

---

#### **19. Temperature Converter**
Write two functions to:
1. Convert Celsius to Fahrenheit.
2. Convert Fahrenheit to Celsius.

---

#### **20. Prime Checker**
Write a function `isPrime` that checks if a number is prime.

---

### **DOM Manipulation Exercises**

#### **21. Button Click Counter**
Create an HTML page with a button. Write JavaScript to count how many times the button is clicked.

---

#### **22. Change Background Color**
Create a button that changes the background color of the page randomly when clicked.

---

#### **23. Create a List**
Write JavaScript that dynamically creates an unordered list and adds list items to it when a button is clicked.

---

#### **24. Hide and Show Text**
Create a button that hides text when clicked and shows it again when clicked a second time.

---

#### **25. Character Counter**
Create an input field and display the number of characters typed in real time.

---

#### **26. Image Carousel**
Create an image carousel where the user can click "Next" and "Previous" buttons to navigate through images.

---

#### **27. Form Validation**
Write JavaScript to validate a form. Ensure fields like email and password meet specific criteria.

---

#### **28. Stopwatch**
Create a simple stopwatch with Start, Stop, and Reset buttons.

---

#### **29. To-Do List**
Build a to-do list app where you can add, delete, and mark tasks as completed.

---

#### **30. Countdown to a Date**
Write a script that displays a countdown to a specific date (e.g., New Year).

---

### **Object and Array Challenges**

#### **31. Merge Two Arrays**
Write a function that merges two arrays without duplicates.

---

#### **32. Flatten an Array**
Write a function `flattenArray` that takes a nested array and flattens it into a single-level array.

---

#### **33. Sort an Array**
Write a function `sortArray` to sort an array of numbers in ascending order.

---

#### **34. Frequency Counter**
Write a function `frequencyCounter` that counts the frequency of each character in a string.

---

#### **35. Group Objects by Property**
Given an array of objects, group them by a specific property.

---

#### **36. Shuffle an Array**
Write a function `shuffleArray` that randomly shuffles an array.

---

#### **37. Find Common Elements**
Write a function `findCommon` to find common elements between two arrays.

---

#### **38. Object Deep Clone**
Write a function `deepClone` that creates a deep copy of a given object.

---

#### **39. Object to Array**
Write a function that converts an object’s keys and values into a two-dimensional array.

---

#### **40. Array to Object**
Write a function that converts an array of key-value pairs into an object.

---

### **Advanced-Level Exercises**

#### **41. Fetch API Data**
Use the Fetch API to get data from an external API and display it on the page.

---

#### **42. Debounce Function**
Write a debounce function that limits how often a function can be called.

---

#### **43. Throttle Function**
Write a throttle function that ensures a function is called at most once every specified time interval.

---

#### **44. Custom Map Function**
Implement your own version of the `Array.map` method.

---

#### **45. Custom Filter Function**
Implement your own version of the `Array.filter` method.

---

#### **46. Tic-Tac-Toe**
Build a simple Tic-Tac-Toe game using JavaScript.

---

#### **47. Calculator App**
Create a calculator app that can perform addition, subtraction, multiplication, and division.

---

#### **48. Snake Game**
Create a simple Snake game using JavaScript and the HTML Canvas API.

---

#### **49. Weather App**
Create a weather app using a free weather API like OpenWeatherMap.

---

#### **50. Quiz App**
Build a multiple-choice quiz app that displays questions, accepts answers, and shows a score.

---

#### **51. Infinite Scroll**
Implement an infinite scroll feature that loads more items when the user scrolls to the bottom of the page.

---

#### **52. Drag and Drop**
Create a drag-and-drop feature where items can be moved between containers.

---

#### **53. Text-to-Speech**
Create a text-to-speech app using the Web Speech API.

---

#### **54. Markdown Previewer**
Create a markdown previewer that converts markdown syntax to HTML in real-time.

---

#### **55. Light/Dark Mode Toggle**
Add a button to toggle between light and dark modes on a webpage.

---

#### **56. Password Strength Checker**
Write a script to check and display the strength of a password as the user types it.

---

#### **57. Search Autocomplete**
Create a search bar with autocomplete suggestions.

---

#### **58. Responsive Navbar**
Build a responsive navigation bar that collapses into a hamburger menu on smaller screens.

---

#### **59. Pagination**
Write a script to paginate data and display a specific number of items per page.

---

#### **60. Chessboard Generator**
Generate a chessboard pattern using JavaScript and CSS.

---

### **Advanced JavaScript Exercises**

#### **61. Recursive Fibonacci**
Write a recursive function `fibonacci(n)` to calculate the nth Fibonacci number.

---

#### **62. Memoized Fibonacci**
Optimize the Fibonacci function using memoization for better performance.

---

#### **63. Async/Await Fetch**
Create a function that fetches data from an API using `async/await`.

---

#### **64. Error Handling**
Write a function that handles errors gracefully using `try...catch`.

---

#### **65. Promise All**
Fetch data from multiple APIs simultaneously using `Promise.all`.

---

#### **66. Event Delegation**
Create a list of items and use event delegation to handle clicks on dynamically added items.

---

#### **67. Closure Example**
Create a function `counter` that uses closures to keep track of a count and has methods to increment, decrement, and get the count.

---

#### **68. Currying**
Write a curried function that adds three numbers: `add(a)(b)(c)`.

---

#### **69. Debounce Button Click**
Implement a debounce function to prevent excessive button clicks.

---

#### **70. Throttle Scroll Event**
Implement a throttle function for optimizing scroll events.

---

### **ES6+ Features**

#### **71. Destructuring Objects**
Create a function that destructures an object and logs specific properties.

---

#### **72. Spread and Rest Operator**
Write a function that uses the spread operator to merge arrays and the rest operator to handle multiple arguments.

---

#### **73. Default Parameters**
Create a function with default parameters to handle missing arguments.

---

#### **74. Template Literals**
Use template literals to generate dynamic HTML content.

---

#### **75. Arrow Functions**
Rewrite a function using an arrow function.

---

#### **76. Object Short Syntax**
Create an object using the short syntax for properties and methods.

---

#### **77. Import/Export Modules**
Write two JavaScript files: one that exports functions and another that imports and uses them.

---

#### **78. Dynamic Imports**
Write a script that dynamically imports a module only when needed.

---

#### **79. Map and Set**
Create an example using `Map` and `Set` to store unique values and key-value pairs.

---

#### **80. WeakMap and WeakSet**
Write a function demonstrating the use of `WeakMap` and `WeakSet`.

---

### **Algorithm Challenges**

#### **81. Longest Substring Without Repeating Characters**
Write a function to find the length of the longest substring without repeating characters.

---

#### **82. Two Sum Problem**
Write a function that takes an array and a target sum and returns indices of two numbers that add up to the target.

---

#### **83. Anagram Checker**
Write a function to check if two strings are anagrams of each other.

---

#### **84. Array Rotation**
Write a function to rotate an array by a given number of steps.

---

#### **85. Merge Sorted Arrays**
Write a function to merge two sorted arrays into one sorted array.

---

#### **86. Binary Search**
Implement a binary search algorithm.

---

#### **87. Bubble Sort**
Write a function to implement the Bubble Sort algorithm.

---

#### **88. Palindrome Number**
Check if a given number is a palindrome (e.g., 121 is a palindrome).

---

#### **89. Roman to Integer**
Write a function to convert a Roman numeral to an integer.

---

#### **90. Deep Object Comparison**
Write a function to deeply compare two objects for equality.

---

### **Framework and Library Exercises**

#### **91. Basic React Component**
Create a React component that displays "Hello, React!".

---

#### **92. State in React**
Create a React component with a button that increments a counter using state.

---

#### **93. React Props**
Create a parent component that passes data to a child component using props.

---

#### **94. React Todo App**
Build a simple Todo app using React with add, delete, and mark as completed functionality.

---

#### **95. React API Fetch**
Use React to fetch and display data from an API.

---

#### **96. Vue.js Basics**
Create a Vue.js app that binds input data to an output field.

---

#### **97. Vue.js Directives**
Use Vue.js directives like `v-if`, `v-for`, and `v-model` in a small project.

---

#### **98. Angular Component**
Create a basic Angular component that displays a list of items.

---

#### **99. Angular Service**
Write a service in Angular to fetch data from an API.

---

#### **100. jQuery DOM Manipulation**
Use jQuery to add, remove, and modify elements on a webpage.

---

### **Practical Web Development Exercises**

#### **101. Local Storage**
Create a script that saves and retrieves data from the browser’s local storage.

---

#### **102. Session Storage**
Write a script that saves data in session storage and displays it on the page.

---

#### **103. Cookie Management**
Create a script to set, get, and delete cookies.

---

#### **104. WebSocket Chat**
Set up a WebSocket connection to build a simple real-time chat.

---

#### **105. File Upload**
Create a form that allows users to upload files and display the uploaded file names.

---

#### **106. Drag-and-Drop File Upload**
Enhance the file upload feature with drag-and-drop functionality.

---

#### **107. Responsive Design Helper**
Write a script to add or remove CSS classes based on the screen width.

---

#### **108. Service Worker**
Create a simple service worker to cache assets for offline use.

---

#### **109. Canvas Drawing**
Use the HTML5 Canvas API to create a simple drawing tool.

---

#### **110. WebGL Basics**
Create a basic 3D object using WebGL.

---

### **Game Development**

#### **111. Simon Game**
Build a Simon game where users repeat sequences of colors and sounds.

---

#### **112. Pong Game**
Create a simple Pong game using the Canvas API.

---

#### **113. Minesweeper**
Build a simplified version of the Minesweeper game.

---

#### **114. Rock, Paper, Scissors**
Write a Rock, Paper, Scissors game that plays against the computer.

---

#### **115. 2048 Game**
Build a 2048 game clone using JavaScript and CSS.

---

#### **116. Typing Speed Test**
Create a typing speed test that tracks the time taken to type a given paragraph.

---

#### **117. Space Invaders**
Build a simple Space Invaders game using JavaScript and the Canvas API.

---

#### **118. Sudoku Solver**
Write a script to solve a Sudoku puzzle.

---

#### **119. Conway's Game of Life**
Create Conway’s Game of Life simulation.

---

#### **120. Memory Game**
Build a memory-matching card game.

---

### **General JavaScript**

#### **121. Countdown Timer with User Input**
Create a countdown timer where the user inputs the duration, and it updates dynamically on the screen.

#### **122. Letter Frequency Counter**
Write a function that counts the frequency of each letter in a string (ignoring spaces and punctuation).

#### **123. Generate Random Hex Color**
Create a function that generates and returns a random hex color code.

#### **124. Split and Rejoin String**
Write a function that splits a sentence into words, reverses their order, and joins them back.

#### **125. Find Missing Number**
Write a function to find the missing number in an array of integers from 1 to n.

#### **126. Custom Reduce Function**
Implement a custom version of the `Array.reduce` function.

#### **127. Intersection of Two Arrays**
Write a function to find the common elements between two arrays.

#### **128. Validate Parentheses**
Check if a string of parentheses is balanced (e.g., `"(())"` is valid, but `"(()"` is not).

#### **129. Convert Number to Words**
Write a function to convert numbers (e.g., 123) into words (e.g., "one hundred twenty-three").

#### **130. Custom Events**
Create a custom event listener system where users can attach and trigger events.

---

### **Date and Time**

#### **131. Human-Readable Time**
Convert a given number of seconds into hours, minutes, and seconds (e.g., 3661 -> "1h 1m 1s").

#### **132. Days Until Next Birthday**
Write a function to calculate the number of days until your next birthday.

#### **133. Stopwatch with Laps**
Create a stopwatch that allows users to record lap times.

#### **134. Countdown to Midnight**
Create a real-time countdown to midnight for the current day.

#### **135. Timezone Converter**
Write a script that converts a given date and time to different time zones.

---

### **Mathematics**

#### **136. GCD and LCM**
Write a function to calculate the greatest common divisor (GCD) and least common multiple (LCM) of two numbers.

#### **137. Generate a Magic Square**
Write a function to generate an n x n magic square (where all rows, columns, and diagonals sum to the same number).

#### **138. Armstrong Numbers**
Check if a given number is an Armstrong number (e.g., 153 = 1³ + 5³ + 3³).

#### **139. Collatz Conjecture**
Write a function to simulate the Collatz sequence for a given number.

#### **140. Pascal’s Triangle**
Generate the first n rows of Pascal’s Triangle.

---

### **String Manipulation**

#### **141. Acronym Generator**
Write a function to create an acronym from a phrase (e.g., "National Aeronautics and Space Administration" -> "NASA").

#### **142. Find the Longest Word**
Write a function to find the longest word in a sentence.

#### **143. Caesar Cipher**
Create a function to encrypt and decrypt messages using the Caesar cipher.

#### **144. Remove Consecutive Duplicates**
Remove consecutive duplicate characters from a string (e.g., `"aabbcc"` -> `"abc"`).

#### **145. Palindrome Partitioning**
Write a function to split a string into all possible palindromic partitions.

---

### **Data Structures**

#### **146. Implement a Stack**
Implement a stack data structure with `push`, `pop`, and `peek` methods.

#### **147. Implement a Queue**
Implement a queue with `enqueue`, `dequeue`, and `peek` methods.

#### **148. Circular Queue**
Extend the queue implementation to make it circular.

#### **149. Binary Search Tree**
Implement a binary search tree with insert, find, and delete methods.

#### **150. Linked List**
Implement a singly linked list with methods for insertion, deletion, and traversal.

#### **151. Trie (Prefix Tree)**
Implement a trie for efficient prefix-based searching.

#### **152. Priority Queue**
Create a priority queue where elements are dequeued based on priority.

#### **153. Graph Traversal**
Implement depth-first search (DFS) and breadth-first search (BFS) for a graph.

#### **154. Dijkstra’s Algorithm**
Write a function to find the shortest path between nodes in a weighted graph.

#### **155. Sudoku Validator**
Write a function to validate a completed Sudoku board.

---

### **Advanced Algorithms**

#### **156. Permutations**
Generate all permutations of a given string or array.

#### **157. Subset Sum**
Find all subsets of an array that sum to a given target.

#### **158. Longest Palindromic Substring**
Find the longest palindromic substring in a given string.

#### **159. Knapsack Problem**
Solve the 0/1 Knapsack Problem using recursion or dynamic programming.

#### **160. Maze Solver**
Write a function to find a path through a maze represented as a 2D array.

---

### **Browser APIs**

#### **161. Geolocation API**
Use the Geolocation API to display the user’s current latitude and longitude.

#### **162. Speech Recognition**
Create a script that converts spoken words into text using the Web Speech API.

#### **163. Speech Synthesis**
Build a text-to-speech app using the Web Speech API.

#### **164. Screen Capture**
Use the Screen Capture API to let users record or share their screen.

#### **165. Clipboard API**
Allow users to copy and paste text using the Clipboard API.

#### **166. Notifications API**
Create a notification system using the Notifications API.

#### **167. Battery Status**
Display the user’s current battery status using the Battery Status API.

#### **168. Device Orientation**
Write a script that logs the orientation of the user’s device.

#### **169. Drag-and-Drop API**
Create a drag-and-drop interface for uploading files.

#### **170. WebRTC Video Chat**
Implement a simple peer-to-peer video chat using WebRTC.

---

### **File and Data Processing**

#### **171. Read Local File**
Allow users to upload a file and display its content in the browser.

#### **172. Parse CSV**
Write a script to parse a CSV file into an array of objects.

#### **173. JSON Formatter**
Create a tool to format and pretty-print JSON strings.

#### **174. Text File Editor**
Create a text editor that allows users to save their work to a file.

#### **175. Image Resizer**
Allow users to upload an image and resize it in the browser.

---

### **Creative Programming**

#### **176. Particle System**
Create a particle system animation using the HTML5 Canvas API.

#### **177. Fractal Tree**
Draw a recursive fractal tree using the Canvas API.

#### **178. Starfield Simulation**
Create a 3D starfield animation using Canvas or WebGL.

#### **179. Interactive SVG**
Use JavaScript to manipulate SVG elements dynamically.

#### **180. Procedural Terrain Generator**
Generate a simple 2D terrain using Perlin noise.

---

### **Data Visualization**

#### **181. Bar Chart**
Build a bar chart using vanilla JavaScript and SVG.

#### **182. Line Chart**
Create a dynamic line chart that updates with live data.

#### **183. Pie Chart**
Build an interactive pie chart using the Canvas API.

#### **184. Heatmap Generator**
Generate a heatmap based on a 2D array of numbers.

#### **185. Tree Diagram**
Visualize a hierarchical tree structure using JavaScript.

---

### **Miscellaneous**

#### **186. Generate a QR Code**
Create a QR code generator using a library like `qrcode`.

#### **187. Currency Converter**
Build a currency converter that fetches live exchange rates from an API.

#### **188. Mortgage Calculator**
Create a script to calculate monthly mortgage payments.

#### **189. Markdown Parser**
Write a script to convert Markdown to HTML.

#### **190. Interactive Calendar**
Build a simple calendar widget with JavaScript.

#### **191. Infinite Image Gallery**
Create an image gallery with infinite scrolling.

#### **192. Expense Tracker**
Build an expense tracker app that calculates and visualizes spending.

#### **193. Weather Dashboard**
Fetch and display weather data for multiple cities.

#### **194. Password Generator**
Create a password generator with customizable length and character options.

#### **195. Browser History Viewer**
Display the user’s browser history in a stylized interface.

---

### **Games and Simulations**

#### **196. Tetris**
Build a playable Tetris game using JavaScript.

#### **197. Breakout Game**
Create a brick-breaking game using the Canvas API.

#### **198. Racing Game**
Simulate a simple racing game with cars that move based on user input.

#### **199. Shooting Gallery**
Create a shooting gallery game with moving targets.

#### **200. AI Tic-Tac-Toe**
Build a Tic-Tac-Toe game where the computer uses AI to make moves.

