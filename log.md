# 100 Days Of Code - Log

### Sol 4: January 8, 2017
**Tasks For Today:**

1. Shallow Copy vs Deep Copy
2. All possible permutations of a String
3. All possible combinations of a String
4. ~~Coursera Week 1~~

**Progress:** 

1. Completed the Videos and Slides of Week 1 for Coursera Algos course. The Programming Assignment is still pending.
2. Whiteboard coding and run through of Dynamic Connectivity solutions: Quick Find, Quick Union, Weighted Quick Union & Weighted Quick Union with Path   Compression Algorithms.
3. Interview Questions answered 2 out of 3.
4. Mock up screens for the Android App started. TODO: Design the Flow and Rest of the screens.
5. Completed the Flow from splash to Login/Register screens.
6. Fixed on the final design and looks great. Imported everything from the Template Android App I had created before.

**Thoughts:**

1. Coursera is pretty good. I honestly didn't expect it to be interesting. So done with Week 1.
2. Have to start with Programming Assignment. Shouldn't take that much time if I figure it out first.
3. Nice Brainstorming for quite some time.
4. It's harder to think of the Flow since I haven't really planned out anything before. I just do things! But it's really important to figure it out before coding it.
5. Got some things going since I had a template. Things that you do today will be worth something someday.

**Link(s) to work:** [https://github.com/sudharti/100-day-challenge-android](https://github.com/sudharti/100-day-challenge-android)

**Summary:**

- Learnt something new with Dynamic connectivity problem.
- Have to start planning and executing stuff and keep track of the progress & time.
- Getting things rolling with Side project. +1

### Sol 3: January 7, 2017
**Tasks For Today:**

1. ~~Question 2.5 Followup~~
2. Shallow Copy vs Deep Copy
3. All possible permutations of a String
4. All possible combinations of a String
5. ~~Finish Chapter 2 in Cracking the coding interview~~

**Progress:** 

1. Question 2.5 Followup: SumListsFoward Iterative Approach completed. Used a stack to push and pop the digits and carry over. **Time: 1 Hour**
2. Question 2.5 Followup: SumListsFoward Recursive Approach. Wasted *1 Hour* trying to figure out a way to do this without a wrapper class or Global variable. But found out that's not possible in this case. **Time: 2 Hours.**
3. Question 2.6 LinkedList Palindrome check. Worked through the different approaches using Stack, Inline reversing and Recursion. Stack and Inline are pretty simple. Recursion should have taken more time. But since it was similar to recursion reversing a list and got a cue from the Book was easy. **Time: 1 Hour**
4. Question 2.6 Additional Reversing a LinkedList. Sub problem solved before solving 2.6. Did three different approaches as Palindrome problem. Learnt Recursion clearly. **Time: 2.5 Hours**.
5. Question 2.7: Intersection. Easy solution. Already have done this before.
6. Question 2.8: Loop Detection: Almost got it right except for the last part. **TODO: Have to read through how it works and Analyse complexity.**

**Thoughts:**

1. I think I am getting familiar to the implementation. Now after white board coding and Algorithmic run through it seems to work just fine.
2. Implemented the iterative Approach which is a no brainer. Have to start the Recursive approach. Since the last problem had a similar solution I guess should be fine.
3. Without the Hint from Book it wouldn't have been possible to pad the lists before adding. Have to start thinking like that.
4. Nice Brainstorming session. Figured out the algorithm but tried to achieve without using a global variable or wrapper. The Book solution uses a wrapper. Got the hint and implementing took hardly 20 mins.
5. Palindrome linked list is an easy solution. I remembered the Stack and Inline solutions. Hardly took 15 mins to write code on White Board. Recursion got me into a Sub problem of reversing a linked list. Again using stack & reversing inline were simple. 
6. When implementing reversing a linked list using recursion learnt how to use Wrapper class sometimes if more than one element needs to be returned from recursive function. This happens when the original calling function requires an object of one type but the recursive calls require some other type.
7. Used to go with an additional variable or Global variable to do this and thought it was inefficient and was a dumb solution. But sometimes you need to work around.
8. Also reversing the LinkedList using recursion the algo derivation and approach were exactly similar to that of the Book even when I didn't refer the Hint. Got Hint for using Wrapper class similar to the SumListsForward recursive solution.
9. Intersection problem was an easy solution. I remembered it from reading it last time. My memory is not as bad as I thought.
10. Loop Detection: Remember reading it and leaving half way through last time. Finished the implementation. Got it almost right except for the last part where the slowPointer is moved to head and both pointers are moved at 1 unit distance. Have to read why that works that way.

**Link(s) to work:** [https://github.com/sudharti/crack-the-code](https://github.com/sudharti/crack-the-code)

**Metrics:**

- Hours Spent: 6.5
- Number of Problems Solved: 5
- Concepts Learned: Recursion, LinkedLists, Wrapper workaround for recursion, Loop Detection in LinkedList
- Split up: SumListsForward(E), ReverseLinkedList(E), isPalindrome(E), Intersection(VE), LoopDetection(E)
- Progress Percentage: Less than 30%

**Summary:**

- Productive Start to the Day! Let's see how the next one goes.
- Recursive solution also worked! Moving on.
- Feel confident with Recursion. You gotta see it to understand it. So True!
- Overall a Pretty Good day. Seeing some progress in Thinking :)

### Sol 2: January 6, 2017

**Tasks For Today:**

***Moving the tasks for tomorrow***

```
1. Shallow Copy vs Deep Copy
2. All possible permutations of a String
3. All possible combinations of a String
4. Question 2.3 through the Chapter of Cracking the coding interview
```
Question 2.4 and 2.5

**Progress:** 

1. Question 2.4 LinkedList Partition problem. Took a while to understand. No solid test cases. Learnt a new technique to add items to head and tail without losing the chaining.
2. Question 2.5 LinkedList SumLists. Already visited concept. Revisited and implemented both Iterative and Recursive solutions. Run through your solution once. TODO: SumListsForward implementation.

**Thoughts:**

1. One thing I realized is that I wrote down the execution on White board but unable to implement in code.
2. That is so Not ME! I am the opposite. If I crack the algo coding is easy. I think it's due to lack of practice lately.
3. Good thing to start something that you know needs improvement!

**Link(s) to work:** [https://github.com/sudharti/crack-the-code](https://github.com/sudharti/crack-the-code)

**Metrics:**

- Hours Spent: 4.5
- Number of Problems Solved: 2
- Concepts Learned: Recursion Basics, LinkedList concepts are familiar
- Split up: Partition LinkedList(E), SumLists(E)
- Progress Percentage: Less than 15%

**Summary:**

It's hard to catch up in the beginning. Once the Momentum builds up everything will fall into place. I feel better than yesterday. DON'T YOU GIVE UP.


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

¯\_(ツ)_/¯

This is not so good for my Streak :( 

Okay I am back on Track. See more TOMO.

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
