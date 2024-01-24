# Project Title

A brief description of what this project does and who it's for

## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Authors

- [@phhduc](https://www.github.com/phhduc)
- [@FarleyCanve](https://www.github.com/farleycanve)

## Roadmap

- [Array]()
- String
- Hash table
- Recursion

## Array

## Introduction

Arrays hold many values of the same type at contiguous memory locations.

## Pros

- Store multiple elements of the same type with one single variable name
- Accessing elements is fast as long as you have the index, as opposed to linked lists where you have to traverse from the head.

## Cons

- Addition and removal of elements into/from the middle of an array is slow because the remaining elements need to be shifted to accommodate the new/missing element. An exception to this is if the position to be inserted/removed is at the end of the array.
- For certain languages where the array size is fixed, it cannot alter its size after initialization. If an insertion causes the total number of elements to exceed the size, a new array has to be allocated and the existing elements have to be copied over. The act of creating a new array and transferring elements over takes O(n) time.

## Time complexity

- Access O(1)
- Search O(n)
- Search (sorted array) Olog(n)
- Insert O(n)
- Intert (at the end) O(1)
- Remove O(n)
- Remove (at the end) O(1)

## Corner cases

- Empty sequence
- Sequence with 1 or 2 elements
- Sequence with repeated elements
- Duplicated values in the sequence
