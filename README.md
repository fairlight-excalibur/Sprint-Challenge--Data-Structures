# Assessing your Data Structures Fu
* The purpose of this exercise is to get you used to being quizzed on _Interview Questions_ commonly asked about Data Structures and their implementation in the JavaScript Language.
* Answers to your written questions will be recorded in *Answers.md* 
* This is to be worked on alone but you can use outside resources. You can *reference* any old code you may have, and the React Documentation, however, please refrain from copying and pasting any of your answers. Try and understand the question and put your responses in your own words. Be as thorough as possible when explaining something. 
* **Just a friendly Reminder** Don't fret or get anxious about this, this is a no-pressure assessment that is only going to help guide you here in the near future. This is NOT a pass/fail situation. 

## Questions
1. What are the order of insertions/removals for the following data structures?
   - **Stack** First in, last out - the first element inserted is the last removed. 
    Ex. if I add a, b, c to the stack, the values will be removed in order of c, b, a
   - **Queue** First in, first out - the first element inserted is the first removed
    Ex. if I add a, b, c to the stack, the values will be removed in order of a, b, c
2. What is the retreival time complexity for the following data structures?
   - **Linked List** O(n)
   - **Hash Table** O(1)
   - **Binary Search Trees** O(logN)
2. What are some advantages to using a Hash Tables over an array in JavaScript?
    Reduced retrieval time [O(log(n)) versus O(n)] (depending on hash table size/hashing/grouping)

## Challenge
If you take a look at the hash-table.js file you'll notice that it has solution code in it. You'll also notice that if you run the tests, they all pass. Your job is to refactor this hash table solution to use **linked lists** for buckets instead of arrays. You're welcome to add another class to the helper file, following the pattern used with LimitedArray.