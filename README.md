# Sort Implemetation

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Available Script](#available-scripts)

## Overview

Sort different data structures (array of numbers, strings, linked lists) in ascending order

### The challenge

Viewers should be able to:

- Sort an array of numbers in ascending order
- Sort strings in ascending order
- Sort the values of a linked list in ascending order
- Avoid code repetition

## My process

- Configure TS compiler
- Install nodemon and concurrently
- Implement sorting algorithm
- Use typeguards for different data structures
- Refactor to extract key sorting logic, rather than if/else statements
- Extract each data structure to a different class
- Take out interface and introduce abstract class, to avoid constant instantiation of Sorter class

### Built with

- Typescript

### What I learned

long method

```ts
collection: number[];

constructor(collection: number[]) {
this.collection = collection;
}
```

shorter method by using a modifier inside the constructor argument

```ts
constructor(public collection: number[]) {}
```

## Available Scripts

In the project directory, you can run:

### `npm start`

logs in the terminal.

The page will reload when you make changes.\
You may also see any lint errors in the console.

```

```
