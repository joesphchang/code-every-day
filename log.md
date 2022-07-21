# Code Every Day

## February 2nd, 2021

Today was crazy, I was learning SQL with the class at General Assembly while I was working on my website. I finally was able to deploy my portfolio through netlify! I created a backend just last night to have the data accessible anytime when I need to update it or add more to it.

I did a code-war challenge that was pretty tough. The code war challenges are a way for me to get better but familiar with what is going on.

```
function getMiddle(s)
{
  //Code goes here!
    let middle = "";

  if (s.length % 2 === 1) middle = [s[(s.length / 2) | 0]];
  else middle = [s[(s.length / 2 - 1) | 0], s[(s.length / 2) | 0]];

  return middle.join("");
}
```

## February 3rd, 2021

This morning, I started doing a code challenge. This one was quite easy to understand. I could of done it either way

```
var summation = function (num) {
  // Code here
 let res = (num * (num + 1)) / 2;
  return res;
}
```

```
var summation = function (num) {
  // Code here
 let results = 0;
 for (let i = 0; i <= num; i++) {
 results += i;
 }
 return results;
}
```

Today I think I'm going to brain-storm ideas for my next project. I'll list it below for myself to think about. I may start watching walk-throughs on CSS tricks and React tricks and code-along with them each day.

- Photography Portfolio (Wire-Frames Needed)
- Spotify App (User Authorization, Wire-Frames Needed)

Today I will tackle Hamburger Menu!

## February 4th, 2021

I did a python code challenge this morning to get familiar with it even more. It was like the homework last night doing a elif statement. I probably could of solved it a little simpler but I did it within one go!

```
def bool_to_word(boolean):
    if boolean == True:
        return 'Yes'
    elif boolean == False:
        return 'No'
```

```
def validate_pin(pin):
    return len(pin) in (4, 6) and pin.isdigit()
```

```
def is_triangle(a, b, c):
    return (a<b+c) and (b<a+c) and (c<a+b)
```

Today I'm going to focus on brain-storming my photography portfolio still.
Finish the hamburger menu and learn how to do animations!

## Februrary 5th, 2021

Took a break this day to refresh my mind.

## Februrary 6th, 2021

Finally got to my wire-frame for the photography portfolio project! (3 P's) I finished it and am happy with the results. I plan on implementing a hamburger menu to allow myself to learn how utilize it. One of the tabs on the nav-bar will have a drop-down menu, which will also be a challenge for myself!

I will be creating a back-end and a front-end for the project. My backend will be MongoDB and my front-end will be ReactJS with regular CSS and HTML5.

## February 7th, 2021

Today woke up to some coding challenges during class. Had a little help but figured out the answers for the questions.

```
def shortest_word(s):
    # your lovely code here!
    return min(len(x) for x in s.split())
```

```
def sum_of_minimums(list):
    # your lovely code goes here!
    return sum(map(min, list))
```

```
def split_strings(s):
    # your lovely code goes here
    if len(s) % 2 == 0:
        result = [s[i:i + 2] for i in range(0, len(s), 2)]
    else:
        result = [s[i:i + 2] for i in range(0, len(s), 2)]
        result[-1] += '_'
    return result
```

By the end of the day, I want to scaffole out my photography portfolio project on my front-end and get all the componenets ready! Finish today's homework. Watch a CSS trick video.

## February 8th, 2021

Today we started off with another code challenge. Learned about using comma slices when assigning multiple variables and also about pythons slice method!

```
def remove_char(s):
    # your code here!
    return s[1:-1]
```

```
def mygcd(x, y):
    # your code here!
    while(y):
        x, y = y, x % y
    return x
```

```
def highest(s):
    # your code here!
    arr, numArr = s.split(' '), []
    for val in arr:
        intNum = 0
        letters = list(val)
        for word in letters:
            intNum += ord(word) - 96
        numArr.append(intNum)
    return arr[numArr.index(max(numArr))]
```

Today I will be focused on leet-code, cleaning up my portfolio website and watching another CSS trick video.

## Feb 10-18, 2022  
Today's Progress: Built out backend on Django  - created models and seeded data on Django admin panel  20% through Angular course on Udemy  - began writing Typescript code - created an Angular app - created components through CLI and in IDE - used HTTP request to pull from our heroku database - property/event binding to pass variables was very rocky, so transitioned back over to React  Built out React app in 2 days  - styled using Material UI, Bootstrap, Animate.css - user authentication is functional, components will display conditionally when user is logged in - user curated data is sent to the database and stored to the API - all components are linked and traverses through the site - error checks are complete, need to add a demo user button and auto refresh page when drinks/comments are added  Thoughts: Hardest week of the course -- creating a Django backend took us about a day and then dove headfirst into learning Angular. 

## Feb 21 - 25, 2022

Progress: Re-did portfolio application. Made signficant changes to my portfolio. Learned new concepts in react and how to utilize react-scroll. Gained extensive knowledge on CSS.

## Feb 28, 2022
Progress: Learned how to create full CRUD back-end with Ruby. Did code-wars 

Turned a boolean into a string. Doing easier challenges to remain consistent with javascript. 
```
function booleanToString(b){
  return b ? 'true' : 'false';
}
```

Today: 
I am working on animations for my portfolio and looking into a new project to do. 

## March 4th, 2022
Progress: 
Today I did a couple of code-wars to refresh my brain on JavaScript. They were pretty easy as I had to create an array and loop through the arguments. I ended up doing it in three tries.

```
function countBy(x, n) {
    var z = [];
    for (i = 1; i <= n; i++) {
        z.push(x * i);
    }
    return z;
}
```

Today: 
I am working on my photography portfolio.

## July 21st, 2022

Progress:
Today I'm taking the time to learn data structures and algorithm. With today's time on learning DS/A is very impoortant when handling data. Whether its traversing through it, adding to it, or deleting somthing out of it. You have to understand how data can be worked with. I've tackled Node nad LinkedList so far on CodeAcademy. Below I will post a snippet of each code block I have created throughout the course so far. My main goal with DS/A is to get familiar with algorithms and be better at explaining and figuring out which method is perfect for a challenged problem. 

I'm not yet ready to tackle leet-codes and I am far from ready to do anything tough when it comes to Technical Interviews. I have skills to create applications and make things work, but when it comes to complex problem. It is one of my biggest weakness as a programer. 

My goal for the mid-year is to be proficient enough to tackle medium-level problems and solve them within a 45 minute time-frame. 

Node
```
class Node {
  constructor(data) {
    // Sets the node to data
    this.data = data;
    // IF no node is after the next block, it ends up being null.
    this.next = null;
  }
    // Sets the next node. 
  setNextNode(node) 
    // Checks if the node is a instance of the node class
    // If the argument isa Node or null, it will set this.next to node
    if (node instanceof Node || node === null) {
     this.next = node;   
    } else {
        // Will throw error if it isn't.
        throw new Error('Not a string!')
    }
  }
    getNextNode() {
    return this.next;
  }
}

// Creates a new node with a value
const firstNode = new Node('I am an instance of a Node!');
// Creates a second node with a new value
const secondNode = new Node('Im the second node!')

// Links firstNode to secondNode
firstNode.setNextNode(secondNode);
console.log(firstNode)
console.log(firstNode.getNextNode())

module.exports = Node;
```

Linked List
```
const Node = require('./Node');

class LinkedList {
  
  constructor() {
    this.head = null;
  }

  addToHead(data) {
    const newHead = new Node(data);
    const currentHead = this.head;
    this.head = newHead;
    if (currentHead) {
      this.head.setNextNode(currentHead);
    }
  }
  addToTail(data) {
    let tail = this.head;
    if (!tail) {
      this.head = new Node(data)
    } else {
      while (tail.getNextNode() !== null) {
        tail = tail.getNextNode();
      }
      tail.setNextNode(new Node(data))
    }
  }
	removeHead() {
    const removedHead = this.head;
    if (!removedHead) {
      return removeHead();
    }
    this.head = removedHead.getNextNode();
    return removedHead.data;
  }
	printList() {
    let currentNode = this.head;
    let output = '<head> '
    while (currentNode !== null) {
      output += currentNode.data + ' ';
      currentNode = currentNode.getNextNode();
    } 
    output += '<tail>'
    console.log(output)
  }
}

module.exports = LinkedList;
```

A coding challenge that I was given at CodeAcademy.
```
const LinkedList = require('./LinkedList');
const testLinkedList = require('./testLinkedList.js');
// Complete this function
const nthLastNode = ( linkedList, n) => {
  let current = null
  tailPointer = linkedList.head;
  count = 0;
  while(tailPointer) {
    tailPointer = tailPointer.next
    if (count >= n) {
      if (!current) {
        current = linkedList.head;
      }
      current = current.next;
    } 
    count++;
  }
  return current;
}

// Test your function yourself:
console.log(nthLastNode(testLinkedList, 4));

// Leave this so that we can test your code:
module.exports = nthLastNode;
```