# Code Every Day 

### February 2nd, 2021

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


### February 3rd, 2021
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

Today I think I'm going to brain-storm ideas for my next project. I'll list it below for myself to think about.

- Spotify App 