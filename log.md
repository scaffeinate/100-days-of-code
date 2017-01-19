# 100 Days Of Code - Log

### Sol 13: January 18, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String
3. ~~Finish Binary Heaps~~

**Progress:**

1. Finish Reading on Binary Heaps on Ctci.
2. This is more than enough to understand the flow of Heaps. https://en.wikipedia.org/wiki/Binary_heap
3. TODO: Read Heaps and HeapSort from Cormen.
4. TODO: How to use Heaps to build Priority Queue.

**Thoughts:**

1. Finally got everything cleared with heaps. Long time Due!
2. Pretty Good explanation on Wikipedia that did it for me.

**Summary:**

- On a more Personal Note Got Clarity on what's pulling me Down! It's Confusion and Regret.

### Sol 12: January 17, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String
3. ~~HashTable Reading complete. Start Binary Heaps~~

**Progress:**

1. Finish Reading Universal Hashing, Probing in HashTable and Perfecrt Hashing Tomo.
2. Expand HashTable once LoadFactor reaches THRESHOLD
3. Started reading on Heaps.

**Thoughts:**

1. HashTable concepts are quite Interesting! It will be even more if I could find time to implement everything.
2. And Yes Cormen is going slow. Have to just run through instead of going deep into the book.
3. Watched a Video for Heaps. Pretty good one to get going. Basic Working: https://www.youtube.com/watch?v=B7hVxCmfPtM

**LinksToWork:**

- [HashTable.java](https://github.com/sudharti/crack-the-code/blob/a1ff88bab272bd0113229319400f09fa99c930c0/datastructures/src/datastructures/hashtable/HashTable.java)
- [HashTableNode.java](https://github.com/sudharti/crack-the-code/blob/a1ff88bab272bd0113229319400f09fa99c930c0/datastructures/src/datastructures/hashtable/HashTableNode.java)

**Summary:**

- Am I going in the Right Direction?!

### Sol 11: January 16, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String
3. ~~Finish Basic HashTable implementation~~

**Progress:**

1. RunThrough of HashTable logic on Whiteboard.
2. Finished Naive HashTable implementation using Division method for Hashing and Chaining to resolve conflicts.
3. Done implementing Stack using 2 Queues.
4. TODO: ~~Finish Reading Universal Hashing, Probing in HashTable and Perfecrt Hashing Tomo.~~

**Thoughts:**

1. I know it's going slow and I don't find much time even to update this Log. Most of my time goes away in reading.
2. It changed my perspective of a Datastructure when I implemented it. HashTable is one example.
3. StackViaQueue is an easy but interesting solution. Glad I am able to remember stuff and implement. ~~TODO: Make a List for the Problems.~~. List of Problems: 

**LinksToWork:**

- [HashTable.java](https://github.com/sudharti/crack-the-code/blob/a1ff88bab272bd0113229319400f09fa99c930c0/datastructures/src/datastructures/hashtable/HashTable.java)
- [HashTableNode.java](https://github.com/sudharti/crack-the-code/blob/a1ff88bab272bd0113229319400f09fa99c930c0/datastructures/src/datastructures/hashtable/HashTableNode.java)
- [StackViaQueues.java](https://github.com/sudharti/crack-the-code/blob/8bce4ece99743769b692021f60ff8ec32cce4da8/cracking-the-coding-interview/src/chapter_3/additional/StackviaQueues.java)
- [MyStack.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/additional/MyStack.java)
- [MyStack2.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/additional/MyStack2.java)

**Summary:**

- Gaining Momentum after the Lousy Weekend. Don't Settle. Be Motivated!

### Sol 10: January 15, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String
3. ~~Finish BST and start studying Basic HashTable Reading~~

**Progress:**

1. Full Day of reading on BST and HashTable.
2. Implemented Minimum, Maximum in BST and also iterative Search which are pretty simple.
3. Studied the part of finding successor of a node in BST.
4. ~~TODO: HashTable implementation~~

**Thoughts:**

1. Reading from Algorithms book. It takes quite a bit of time. So very little coding today.

**LinksToWork**

- [BinarySearchTree.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/tree/BinarySearchTree.java)
- [TreeNode.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/tree/TreeNode.java)

**Summary:**

- HashTable implementation next. After that should gain some momentum. Until then it's gonna be SLOW.

### Sol 9: January 14, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String
3. ~~Binary Search Tree Implementation with Delete & Tree Traversal~~

**Progress:**

1. BinarySearchTree: Finish Delete and Balance BST. Was stuck with deleting the leaf nodes. **REMEMBER: Java is always Pass By Value**. Was trying to set a node to null and used a void function and thought making the reference to null will change the link also to reflect. But since it's pass by value when recursive function is called with the an object the value of it is passed and since I am making it NULL it wont reflect if I dont return. For eg: Integer a = 10; Integer b = a; b = null; //will not reflect back in a. But take this ```List<Integer> list = new ArrayList<Integer>(); list.add(1); List<Integer> list2 = list; list2.add(2); will make both the lists [1, 2] but if I made list2 = null; then it won't reflect in list. Since I am assigning using =```
2. Breadth First and Depth First Traversal
3. Read the Algorithms Book on the topics covered in Ctci so far.

**Thoughts**

1. Deep thought on how the objects point to the same memory location but reference is still different. If I made one null then it reflects in the value it holds and doesn't affect the other object. But if I made some changes then both reflects if it points to same address. Bad explanation I know. But for Self NOTE.
2. BFS and DFS Done. Quite easy. Although now I understood how to count the level in BFS which I didn't catch it up last time I was doing.

**LinksToWork**

- [BinarySearchTree.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/tree/BinarySearchTree.java)
- [TreeNode.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/tree/TreeNode.java)

**Summary:**

- BFS done. Next Reading concepts.

### Sol 8: January 13, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String
3. ~~Binary Search Tree Implementation~~

**Progress:**

1. BinarySearchTree: Created basic implementation of BST. insert, preOrder, inOrder and postOrder completed.
2. BST Delete Algorithm: Saw how to perform delete on BST. ~~TODO: Need to complete the implementation.~~

**Thoughts**

1. BST implementation is not that hard as I thought. I thought it might be since it's been a while I visited these concepts.
2. BST delete is a problem. Balancing.Hmmm...

**LinksToWork**

- [BinarySearchTree.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/tree/BinarySearchTree.java)
- [TreeNode.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/tree/TreeNode.java)

**Summary:**

- WIll finish the delete implementation tomorrow.

### Sol 7: January 12, 2017
**Tasks For Today:**

1. All possible permutations of a String
2. All possible combinations of a String

**Progress:**

1. Question 3.6: Add Implementation for AnimalShelter problem
2. CircularLinkedList started implementation. TODO: Complete this one
3. Started reading on Binary Tree and BST from Chapter 4

**Thoughts**

1. Book solution for 3.6. Nothing to think about.
2. CicularLinkedList really simple. Need to complete this one out whenever I get the time.
3. Chapter 4 might take some time since it's one Trees and Graphs. Non Linear DS :P

**LinksToWork**

- [AnimalShelter.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/AnimalShelter.java)
- [Shelter.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/Shelter.java)

**Summary:**

- Lots there to read. Hmmm. This might take a while...

### Sol 7: January 11, 2017
**Tasks For Today:**

1. ~~Shallow Copy vs Deep Copy~~
2. All possible permutations of a String
3. All possible combinations of a String
4. ~~Finish Chapter 3 in Ctci~~

**Progress:**

1. Question 3.5: Sort Stacks. Added my solution and it worked. Pretty simple. Do a insertion sort using two stacks and a temp variable. **TODO: Using 3 stacks do Quick sort**
2. Question 3.6: AnimalShelter. Not much of a logic problem. Object Oriented design is key for this otherwise simple problem. ~~Didn't add implementation yet.~~
3. Shallow Copy vs Deep Copy: Read through Shallow vs Deep Copy. Reference: [http://javaconceptoftheday.com/difference-between-shallow-copy-vs-deep-copy-in-java/]. **TODO: Implement Solid Example using clone for Shallow vs Deep copy**. So ```clone()``` does a shallow copy of an object if the Class implements ```Cloneable``` interface and has a implementation of ```clone()```. So in Shallow copy/clone the variables(primitives) values are copied on to the new object as a new copy but the sub references are not. Say a class has a List reference then when cloning the object of that class will not create a copy of the list. It just points to the same reference. Any modification done to the list of cloned object is reflected in original object. But when the reference is assigned again using **=** then new memory reference is created. **NOTE: This is why immutables like Integer and String inside the class are not affected but references like List are modified.**
4. Implemented DoubleLinkedList: Pretty straight forward implementation.

**Thoughts:**

1. Thought through and figured out Sort stacks and found out the Book had the same solution. It's easy but I learnt to use the things I pick up. Win for me!
2. AnimalShelter: Used multiple references in the same LinkedList. But kind of hard to maintain and the original design of Abstract Animal class with Dog & Cat extending it had to be changed because of that. So went with the Book solution which is much cleaner.
3. Finally cleared the doubt I had for so many days now. High level idea of how I thought about Object & references.
4. No Brainer!

**Metrics:**

- Number of Problems solved: 2
- Problems solved: SortStacks, AnimalShelter, ShallowDeepCopy
- DS problem: DoubleLinkedList
- Hours taken: 5 Hours
- Concepts Learnt: Using Two stacks to sort, Object Oriented Design to solve problems, Shallow vs Deep copy and clone() implementation in Java.

**Links to Work:**

- [SortStack.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/SortStack.java)
- [DeepShallowCopy.java](https://github.com/sudharti/crack-the-code/blob/master/random/src/random/DeepShallowCopy.java)
- [DoubleLinkedList.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/lists/DoubleLinkedList.java)

**Summary:**

- Little implemented. More learnt. Slow Progress.
- Need to clear my doubts/start tracking the questions I have whenever possible.
- Start implementing DS/DS problem everyday. Can complete the basic DS implementation within a few days.

### Sol 6: January 10, 2017
**Tasks For Today:**

1. Shallow Copy vs Deep Copy
2. All possible permutations of a String
3. All possible combinations of a String
4. ~~Next Two problems in Chapter 3 Implementation ~~

**Progress:**

1. Question 3.3: SetOfPlates: Went with a HashMap implementation initially to realize that it's harder to manage and ArrayList is much simpler with the same complexity. Fixed SetOfStacks without the Rollover part.
2. Question 3.3: SetOfPlatesWithRollover: If popAt(i) is to be implemented then the incomplete stacks need to be filled otherwise there would be stacks in the middle which are incomplete. So for a complete implementation followed the Book solution. So when we popAt(i) we shift the elements from the subsequent stacks. For this a TwoWay stack with popBottom() and pop() is required. Used an iterative instead of recursive as given in Book.
3. Question 3.4: Queue via Stacks: It's an easy solution. But for dynamically growing queue there needs to be a lot of shifts. There are two ways to look at this problem:
  - Use a stack for push and another one for pop and peek. Shift the elements between the stack whenever the actions are called. This is a bit costly considering n which is large.
  - The Optimal way as per the Book would be to use a Stack for older elements and one for newer elements. Whenever we do a pop() or peek() the oldstack is checked if empty and if so we move all the elements from the new stack. push() always happens in the new stack. In this way the shift happens only when oldstack is cleared out.
4. ~~Question 3.5: SortStacks: Started but couldn't think anything clear. So pushed for next day.~~

**Thoughts:**

1. The normal version is really easy to implement and there is no need of HashMap. The only reason I thought of a hashmap was for the followup which had popAt(i). But failed to account for the shifting of elements. If the stacks can be left incomplete then it might work.
2. The Book approach is simple. Took some time to implement. I guess I couldn't think clear today.
3. Queue via stacks is a long known solution. Put in one stack and transfer to other stack and pop() will create a queue. Anybody knows that. But when designing a queue that can add elements dynamically the number of shifting need to be reduced.
4. SortStack. Couldn't think clearly so pushing it for tomo.

**Metrics:**

- Number of Problems solved: 2
- Problems solved: Set of Stacks, QueueviaStacks
- Hours taken: 5 Hours
- Concepts Learnt: Using Two stacks to effectively create a queue.

**Links to Work:**
- [SetOfStacks.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/SetOfStacks.java)
- [SetOfPlates.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/SetOfPlates.java)
- [SetOfStacksRollover.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/SetOfStacksRollover.java)
- [SetOfPlatesRollover.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/SetOfPlatesRollover.java)
- [MyQueue.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/MyQueue.java)
- [QueueViaStacks.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/QueueViaStacks.java)

**Summary:**

- Kinda Bad day!
- One week into it. Not Bad :|


### Sol 5: January 9, 2017
**Tasks For Today:**

1. Shallow Copy vs Deep Copy
2. All possible permutations of a String
3. All possible combinations of a String
4. ~~First two problems in Chapter 3 + Implementation of Stack & Queue~~

**Progress:**

1. Read through Chapter 3 of ctci on **Stack and Queue**. Implemented basic Stack & Queue Datastructures.
2. Question 3.1: **ThreeinOne** - The question was how to design an array to store 3 stacks. Using a FixedSizeStack approach in which each sub stack has a fixed size above which we don't grow it further. When the size is fixed it's easy to calculate the offset to push(), pop() and peek(). So it runs in O(1) time.
3. Question 3.1: ThreeinOne - **TODO: Think through and implement the VariableSizeStack approach (This can be tricky to implement).**
4. Question 3.2: **StackMin** - Add method min() to the Stack which returns the minimum in O(1) time.
  - First approach: By keeping a variable minValue and updating it while push(). 
     But when the minVal is popped from the stack then we need to find the least element in stack and update minVal. Worst case O(n) for popping. And if the second minimum is at the bottom of the stack then n traverses can be costly especially if n is huge.
  - Alternate approach: Store the min value in the NodeWrapper which holds the current node and the min value at the level. 
    So when popped we get the next min element at the next level. So top.min will always hold the minimum value.
    
5. Question 3.3: **SetOfPlates** - Design a datastructure SetOfStacks to hold multiple stacks. Literally imagine like a set of plates when overflows we shift to the next stack.
   Follow up: Add a method popAt(i) which removes the top at sub stack i.
  - First Approach: Used a HashMap to store the stack with stackNum as the key. So access to the stack is still O(1). 
    So push(), pop() and peek() can be performed on the most recent stack at O(1). Extra space: O(n). 
    Problem with this approach is when popAt(i) is called the sub stack is cleared but not completely filled or in worst case can be empty. ~~**TODO: Incomplete solution. Need to think the edge cases and finish this one out.**~~
  - Second Approach: ~~**TODO: Shift the stack elements.**~~

**Thoughts:**

1. Revised concepts on Stack and Queue. Simple implementations. But will be helpful.
2. Got the question wrong at first. Have to read between the lines in the question to fully understand it. Simple to figure out after understanding the question.
3. VariableStackSize could be tricky one to implement. And don't know why the Book solution uses a circular array. It must be optimized but I don't see how all the cases are handled.
4. StackMin thought of the first solution. But discarded when I found that it has a O(n) worst case. Using a wrapper to store the min +1. Have to start thinking without boundaries to achieve the intended time complexity.
5. SetOfPlates is still in progress. Thought about it but didn't handle to edge cases. I felt that even while testing yesterday. So have to work this one out. Second Approach should be done today.

**Metrics:**

- Number of Problems solved: 4
- Problems solved: Stack, Queue, ThreeinOne*, StackMin, SetOfPlates*
- Hours taken: 5 Hours
- Concepts Learnt: Using a Wrapper class to optimize, Used some concepts learnt to achieve O(1) like storing the min at the top for O(1) access.

**Links to Work:**

- [CustomStack.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/stack/CustomStack.java)
- [CustomQueue.java](https://github.com/sudharti/crack-the-code/blob/master/datastructures/src/datastructures/queue/CustomQueue.java)
- [FixedSizeStack.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/FixedSizeStack.java)
- [CustomStackMin.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/CustomStackMin.java)
- [StackMin.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/StackMin.java)
- [SetOfStacks.java](https://github.com/sudharti/crack-the-code/blob/master/cracking-the-coding-interview/src/chapter_3/stack_queue/SetOfStacks.java)

**Summary:**

- Overall NOT BAD! But could have done better.
- **Have to start thinking edge cases as those are Really IMPORTANT**.
- ***Still haven't learnt ShallowCopy vs DeepCopy :(***

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
4. Mock up screens for the Android App started. **TODO: Design the Flow and Rest of the screens.**
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
6. Question 2.8: Loop Detection: Almost got it right except for the last part. ~~**TODO: Have to read through how it works and Analyse complexity.**~~

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
