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

## July 22nd, 2022
Progress:
Today I am learning about Queues and Stacks on CodeAcademy. Also, I recently bought a uDemy course on Data Structures and Algorithms. For my ultra-learning experience, this is the main topic I plan on tackling to understand DS/A takes amount of time and effort. Most importantly practice and repetition. At the end of each lesson, I'm usually given problems to solve that are similar problems that you would see on Leetcode. It is always great practice to test yourself and see if you can ace it in the hole. 

Going through Queues was rough. I had a hard-time trying to focus and recognize the patterns that was given to me. I think Queues are something I need to look at over again. 

```
class Stack {
  constructor(maxSize = Infinity) {
    this.stack = new LinkedList();
    this.size = 0;
    this.maxSize = maxSize;
  }

  push(value) {
    this.stack.addToHead(value);
  }

  pop() {
    if (this.size > 0) {
    const value = this.stack.removeHead();
    this.size --;
    return value;
    }  else {
      console.log('Stack is empty.')
    }
  }

  peek() {
    if (this.size > 0) {
      return this.stack.head.data;
    } else {
      return null;
    }
  }

}
```
## Two - Sum
```
var twoSum = function(nums, target) {
    // create a new Map
    let map = new Map();
    // loop over the nums
    for (var i = 0; i < nums.length; i++) {
      // store the compliment between current num and the target
	  // if target 10, and num[i] = 6 there is only ONE number that we can add to 6 to make it 10. 
        // That is the number 4. We call it the compliment because it compliments 6 to hit the target 10.
        // EG if target = 10 and nums[i] = 6....  10 - 6 = compliment = 4
        let compliment = target - nums[i];
        // What we are going to do is check if the compliment exists in the hashmap.
        // If the map already contains the compliment we will return an array with the index of the compliment. And current index.
        // When calling map.get(compliment) in the return, this will return the VALUE at that key 
        if ( map.has(compliment)) {
           return [map.get(compliment), i];
           } else {
               // Since the compliment does not exist as a key in the map.
               // We store the key num[i], and index as the value for that key.
               map.set( nums[i] , i)
           }

    }
    // If there is no compliment we will return an empty array. 
    return [];
};
```

## July 25th, 2022
Progress:
Today I'm doing a Leet code challange 'Valid Anagram' where it checks if a word has repeating letters to another word. I start to realize that when solving Array Code Challenge, HashMaps are mainly utilzie to solve these challenges. A hashmap is utilize to surface whether or not the same letters/numbers will show up. Its a great way to sort through an array to figure out certain problems.

## Key tips on Hash Tables / Hash Maps
```
declare hashCode variable with value of 0

for each character in the key
  add the sum of the current character code value and hashCode to hashCode

return hashCode
```

Here's the code

```
  var isAnagram = function(s, t) {
    if (s.length !== t.length) {
        return false;
    }
    let sMap = {};
    let tMap = {};
    for (let i = 0; i < s.length; i++) {
        if (sMap.hasOwnProperty(s[i])) {
            sMap[s[i]]++;
        } else {
            sMap[s[i]] = 1;
        }
        if (tMap.hasOwnProperty(t[i])) {
            tMap[t[i]]++;
        } else {
            tMap[t[i]] = 1;
        }
    }
    for (let k in sMap) {
        if (sMap[k] !== tMap[k]) {
            return false;
        }
    }
    return true;
};
```

## July 29th, 2022
Missed a couple days due to a coding challenge that I didnt successfully do well in. I'm happy I tried and tackled it. I totally forgot to turn it in, so I'm a little embarassed by that notion. I now know why I'm a front-end developer and not a full-stack engineer. I love coding, but I also like creating websites and maintaining them. 

Today I'm following a LeetCode 101: The 14 Patterns Introduction where a man named Vinz Angelo Madrigal is going through a powerpoint on 14 different patterns. He touches up on Sliding Window and walks through a challenge that utilizes it. 

Here's the code I got from working alongside with him and it worked.

```
var numOfSubarrays = function(arr, k, threshold) {
    // Find the sum of the first k ints
    let sum = 0;
    // Add to counter if the average of sum over k is equal to or greater than the threshold
    for ( let i = 0; i < k; i++) {
        sum += arr[i];
    }
    let average = sum / k;
    let counter = 0;
    if (average >= threshold) {
        counter++;
    }
    // For the rest of array
    for (let j = k; j < arr.length; j++) {
        // slide window up by one element
        sum -= arr[j - k];
        sum += arr[j];
        // Calculate the average of these k elements
        let currAverage = sum / k;
        // If the k element's average is greater than the threshold 
        if (currAverage >= threshold) {
            counter++;
        }
    }
    // Return counter
    return counter++;
};
```

## August 4th, 2022
Had a long vacation but coming back to doing hashmaps and a udemy course on DS and Algos. 