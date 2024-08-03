---
layout: post
title: "Javascript most used array methods"
date: 2024-08-03 00:18:00 +0530
categories: technical-blog
tags: technical-blog javascript arrays revision
---

## About
Following is a content containing quick reference with examples for most common use cases using javascript array methods.

### Deleting an element from a specific index
```
function deleteElement(targetArray, deleteAtThisIndex) {
   targetArray.splice(deleteAtThisIndex, 1);
   return targetArray;
}

let myArray = [1, 2, 3, 4, 5];
console.log(deleteElement(myArray, 2)); // Output: [1, 2, 4, 5]
```

### Check if an element exists in an array

```
let fruits = ['apple', 'banana', 'cherry'];
let hasBanana = fruits.includes('banana'); // true
```