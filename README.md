![computa](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.reactiongifs.com%2Fr%2Fmnytu.gif&f=1&nofb=1)
<!-- ![boomsters](https://viralviralvideos.com/wp-content/uploads/meme/2014/03/GIF-That-awkward-moment-when-you-use-Google-to-search-for-Google.gif) -->

# Shmoogle Interview

A non-insane starter list maybe...

---

## Arrays

### 1. Sum of Two Values 💚

Given an array of integers and a value, determine if there are any two integers in the array whose sum is equal to the given value.


```
Tricky-Trick: 
Use a hashmap to log the complements of each number.
Complements represent the other number you're looking for that to make target sum.
When you find one your looking for you're done!
```

[leetcode](https://leetcode.com/problems/two-sum/) | [youtubes](https://www.youtube.com/watch?v=KLlXCFG5TnA)


### 2. Move Zeros to the Left 💚

Move all zeros to the left of an array while maintaining its order.


```
Tricky-Trick: 
Depends on zeros to end or begining. Either way use pointers. 
If zeros to end, use a left pointer and iterate the right normally. 
If zeros to beginning make left and right pointers meet in the middle.
```

[leetcode](https://leetcode.com/problems/move-zeroes/) | [youtubes](https://www.youtube.com/watch?v=aayNRwUN3Do)

---

## Linked Lists

### 3. Delete Node with Given Key 💚

You are given the head of a linked list and a key. You have to delete the node that contains this given key.
Harder version, you aren't given the head but just the node. Sit on that one.

```
Tricky-Trick:
No trick if you're given the head and a target val.
If you're just given the node you basically turn the node into it's neighbor.
Also disconnect it's neighbor from the linked list just in case.
```

[leetcode](https://leetcode.com/problems/delete-node-in-a-linked-list/) | [youtube (related not exact problem)](https://www.youtube.com/watch?v=XVuQxVej6y8)


### 4. Copy Linked List with Arbitrary Pointer 🧡

You are given a linked list where the node has two pointers. The first is the regular ‘next’ pointer. The second pointer is called ‘arbitrary_pointer’ and it can point to any node in the linked list.
 
Your job is to write code to make a deep copy of the given linked list. Here, deep copy means that any operations on the original list (inserting, modifying and removing) should not affect the copied list.

```
Tricky-Trick: Make a crazy hashmap where the keys are the original nodes and the values are new copied versions of the nodes. Then iterate back through and something something...
```

[leetcode](https://leetcode.com/problems/copy-list-with-random-pointer/) | [youtubes](https://www.youtube.com/watch?v=5Y2EiZST97Y)

---

## Trees

### 5. Mirror Binary Trees 💚

Given the root node of a binary tree, swap the 'left' and 'right' children for each node. 

```
Tricky-Trick:
```

[leetcode](https://leetcode.com/problems/invert-binary-tree/) | [youtubes](https://www.youtube.com/watch?v=OnSn2XEQ4MY)


### 6. Check if Two Binary Trees are Identical 💚

Given the roots of two binary trees, determine if these trees are identical or not.


```
Tricky-Trick:
```

[leetcode](https://leetcode.com/problems/same-tree/) | [youtubes](https://www.youtube.com/watch?v=vRbbcKXCxOw)

---

## Strings

### 7. String Segmentation 🧡

Given a dictionary of words and an input string tell whether the input string can be completely segmented into dictionary words.


```
Tricky-Trick:
```

[leetcode](https://leetcode.com/problems/word-break/) | [youtubes](https://www.youtube.com/watch?v=Sx9NNgInc3A)


### 8. Find all Palindrome Substrings 🧡

Given a string find all non-single letter substrings that are palindromes.


```
Tricky-Trick: Totally forgot, maybe pointers?
```

[leetcode](https://leetcode.com/problems/palindromic-substrings/) | [youtubes](https://www.youtube.com/watch?v=4RACzI5-du8)

---

## Dynamic Programming

### 9. Largest Sum Subarray 💚

Given an array, find the contiguous subarray with the largest sum.


```
Tricky-Trick: Something with pointers and a running sum... Kadanes algorithm?
```

[leetcode](https://leetcode.com/problems/maximum-subarray/) | [youtubes](https://www.youtube.com/watch?v=5WZl3MMT0Eg)

---

## Math and Stats

### 10. Determine if the Number is Valid 💔

Given an input string, determine if it makes a valid number or not. For simplicity, assume that white spaces are not present in the input.


```
Tricky-Trick:
```

[leetcode](https://leetcode.com/problems/valid-number/) | [youtubes](https://www.youtube.com/watch?v=-6H2UFV68RI)

---

## Backtracking

### 11. Print balanced brace combinations 🧡

Print all braces combinations for a given value 'N' so that they are balanced.


```
Tricky-Trick: Make a shared return array and count integers for opening and closing prenetheses count then recurse down to a base case related to the counts and n. Kinda remember it but might be missing something?
```

[leetcode](https://leetcode.com/problems/generate-parentheses/) | [youtubes](https://www.youtube.com/watch?v=s9fokUqJ76A)

---

## Graphs

### 12. Minimum Spanning Tree 🧡

Find the minimum spanning tree of a connected, undirected graph with weighted edges.


```
Tricky-Trick:
```

[leetcode (multiples)](https://leetcode.com/tag/minimum-spanning-tree/) 

[leetcode](https://www.youtube.com/watch?v=f7JOBJIC-NA)| [youtubes](https://www.youtube.com/watch?v=f7JOBJIC-NA)

---

## Design

### 13. Implement a LRU Cache 🧡

Least Recently Used (LRU) is a common caching strategy. It defines the policy to evict elements from the cache to make room for new elements when the cache is full, meaning it discards the least recently used items first.


```
Tricky-Trick: Use a linked list representing a queue and a hashmap for looking up nodes.
```

[leetcode](https://leetcode.com/problems/lru-cache/) | [youtubes](https://www.youtube.com/watch?v=7ABFKPK2hD4)

---

## Sorting and Searching

### 14. Find the High and Low Index 🧡

Given a sorted array of integers, return the low and high index of the given key. Return -1 if not found. The array length can be in the millions with many duplicates.


```
Tricky-Trick:
```

[leetcode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | [youtubes](https://www.youtube.com/watch?v=4sQL7R5ySUU)


### 15. Merge Overlapping Intervals 🧡

You are given an array (list) of interval pairs as input where each interval has a start and end timestamp. The input array is sorted by starting timestamps. You are required to merge overlapping intervals and return output array (list).


```
Tricky-Trick: Sort it like a pleb and make a new merged array to push into.
```

[leetcode](https://leetcode.com/problems/merge-intervals/) | [youtubes](https://www.youtube.com/watch?v=44H3cEC2fFM)
