# 100 Days Of Code - Log

### Sol 0: January 4, 2017

**Today's Progress:** 

1. Revisited Question 1.4 to 1.9 in cracking the coding interview.
2. Question 1.4 Palindromic Permutation. Understood the logic behind bit vector manipulation. Similar to the one in 1.2. Learned how to negate a bit and also to check if it's a power of two:
  - To negate nth bit do AND with (Integer.MAX) - (2 ^ n). 
  For eg: 010001 where 2nd position needs to be negated. 
  111111 - 010000 = 101111; 010001 & 101111 = 000001
  - To check power of 2 condition: [n & (n-1) = 0]. Eg: 010000 & 001111 = 000000; 010001 & 010000 = 010000;
3. Question 1.5 One Away: Changed to a clear logic. Replacing and Inserting a character has similar logic with just pointer position changing.
4. Question 1.6: StringCompression. Piece of Cake!
5. Question 1.7: RotateMatrix. Implemented it again to get it cleared. Note: Swapping 4 variables.
6. Question 1.8: ZeroMatrix. Easy one. Revisited the best implementation[Book].
7. Question 1.9: StringRotation. Easy one. Remember the way from Book.
8. LinkedList implementation. Basic.

**Thoughts:** 

1. Very Slow Progress Today.
2. Learned something in bit manipulation.
3. Struggled with RotateMatrix. Forgot the logic although really simple one. Always write on paper to solve Matrix problems.
4. ZeroMatrix I remembered the best method but didn't have the confidence to work it out :(
5. String Rotation was a interesting one!
6. +1 to myself to implement Generics in LinkedList :)

**Link(s) to work:** https://github.com/sudharti/cracking-the-code/

**Hours Spent:** 3.5 hours

End of Chapter 1 and LinkedList Implementation. Chapter 2 Begins Tomorrow. Some rough start to the Streak :|

### Sol 1: January 5, 2017

**Today's Progress:** 

1. Revisited LinkedList chapter in cracking the coding interview book.
2. Solved a really simple question to link up alternate nodes. [AlternateLinking.java](https://github.com/sudharti/cracking-the-code/blob/master/src/chapter_2/additional/AlternateLinking.java). Took almost an Hour and Half for some reason :(
3. Question 2.1 Revisited. Really simple one. Took a long time to complete this one.
4. Corrected functionality in CustomLinkedList implementation of mine.
5. Took a break and looked at the solution again. Did some whiteboard coding.
6. Question 2.2 Revisited. FindKthElement from Last. Practised on Whiteboard. **Recursive solution TODO.**
7. Question 2.3. This caused the confusion.
8. ***The solution to delete a node if:
  1. Address of the node/Reference is not used anywhere. Since we are copying the data alone the object may differ.
  2. THIS DOES NOT WORK WITH THE LAST ELEMENT OF THE LINKED LIST!!!!
  3. Use this only if the head pointer is unknown and you wanna delete in O(1).
  4. Avoid using elsewhere. This had caused the problem for the previous questions.***
9. **Complexity for Insertion and Deleting is O(n)**.
```
// Nice and Easy way to delete the contents of a Node
// Works only on certain conditions
node.data = node.next.data;
node.next = node.next.next;
```

**Thoughts:** 

1. Bad F****** Day! Some Mind Block caused me to work so slow. Even simple logic seemed difficult.
2. I am cursing myself now.
3. Took 1.5 hours for a simple solution I thought at first. But the worst was yet to come.
4. Even those who are new to programming will find it easier. The thing is I knew the logic and Algo and Implementing looked hard for me. GOD I am so f***** up if this continues.
5. Not much of Learning today. Worse than ever to solve the most easiest problems in the WORLD!!!!!
6. -1 to myself to implement Generics in LinkedList :)
7. The thing is I was going throught the solution for 2.3 in the afternoon and thought wow a great optimized way. Little did I know the restrictions of it :P.
8. Tried to use those in 2.1 and what a waste of time :O
9. Complexity of LinkedList insertion and deletion is O(n). I knew that at the back of my head. What was I thinking?
10. Understood two things:
  1. NEVER Do Problem solving when frustrated or if there is a mind block. Take a few minutes. 
  2. White Board Coding is fun! I really was nervous about it. PROBLEM Solving is FUN.

**Link(s) to work:** https://github.com/sudharti/cracking-the-code/

**Hours Spent:** 5 hours [Duh!]. 3 Hours due to my stupid mistake. 

\_(ツ)_/¯

This is not so good for my Streak :( 

Okay I am back on Track. See more TOMO.

### Sol 2: January 6, 2017

**Tasks For Today:**
- Shallow Copy vs Deep Copy
- Question 2.3 through the Chapter of Cracking the coding interview

**Progress:** 

**Thoughts:**

**Link(s) to work:**

**Metrics:**

- Hours Spent:
- Number of Problems Solved:
- Number of Concepts Learned:
- Split up: 
- Progress Percentage: 

**Summary:**
