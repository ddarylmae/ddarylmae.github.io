---
layout: post
title: Imperative vs Declarative Programming
---

Imperative and Declarative Programming are common programming paradigms. According to Wikipedia, [Programming Paradigms][1] are a way to classify programming languages based on their features. It can also be referred to as a style or a way of coding. 

### Imperative
Imperative style of coding is a paradigm wherein the programmer explicitly states how to get an output by following a certain flow of operation.

### Declarative
Declarative Programming on the other hand, is a style wherein the programmer merely describes what output is wanted without stating how to get the output.

### Context
Declarative: Asking your friend to buy you Cookies and Cream flavored ice cream
Imperative: Asking your friend to go to SuperMarket XYZ at 6:00pm and buy a 2L tub of Cookies and Cream flavored ice cream. 

### C# Example
Imperative
```c#
var liveNeighbours = 0;
foreach(neighbour in neighbours){
    if(neighbour == Cell.Live) {
        liveNeighbours ++;
    }
}
```

Declarative
```c#
var liveNeighbors = neighbours.Count(neighbour => neighbour == Cell.Live);
```

[1]: https://en.wikipedia.org/wiki/Programming_paradigm