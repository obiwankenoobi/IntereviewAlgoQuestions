# Intereview Algorithm Questions 
## Implemented in Javascript

This repo will have my solutions for a lot of the questions asked by the big companies, together with a [medium](http://www.google.com) article for each of them to explain the process. 


<details>
  <summary>Find all dice roll options - asked by Facebook</summary>
  <p>
    <blockquote>
        Given N represent the number of dices you have,
        output all the possibilities you can have.
    </blockquote>
  </p>
  <a href="./allDiceOptions.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-10-roll-the-dice-b88c21b3f6e4">explanation</a>
  <br>
  <br>
</details>


<details>
  <summary>Find The Word In Board - asked by Microsoft</summary>
  <p>
    <blockquote>
    Given a 2D matrix of characters and a target word,
    write a function that returns whether the word can be found
    in the matrix by going left-to-right, or up-to-down.
    For example, given the following matrix:

    [
        ['F', 'A', 'C', 'I'],
        ['O', 'B', 'Q', 'P'],
        ['A', 'N', 'O', 'B'],
        ['M', 'A', 'S', 'S']
    ]

and the target word 'FOAM', you should return true, since it's the leftmost column.
Similarly, given the target word 'MASS', you should return true, since it's the last row.
    </blockquote>
  </p>
    <br>
  <a href="./isWordExistInBoard.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-2-find-the-word-on-board-bba7756a7677">explanation</a>
  <br>
  <br>
</details>

<details>
  <summary>Two Identical Subsets - asked by Facebook</summary>
  <p>
    <blockquote>
        Given a multiset of integers, return whether it can be partitioned into two subsets whose sums are the same.
        For example, given the multiset {15, 5, 20, 10, 35, 15, 10}, it would return true, since we can split it up into {15, 5, 10, 15, 10} and {20, 35}, which both add up to 55.
        Given the multiset {15, 5, 20, 10, 35}, it would return false, since we can't split it up into two subsets that add up to the same sum.
    </blockquote>
  </p>
  <a href="./twoIdenticalSubsets.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-6-identical-subsets-9c7d787072c1">explanation</a>
  <br>
  <br>
</details>

<details>
  <summary>Perfect Number - asked by Microsoft</summary>
  <p>
    <blockquote>
        A number is considered perfect if its digits sum up to exactly 10.
        Given a positive integer n, return the n-th perfect number.
        For example, given 1, you should return 19. Given 2, you should return 28.
    </blockquote>
  </p>
  <a href="./isPerfectNumber.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-3-is-perfect-number-cb3eb963ae51">explanation</a>
    <br>
    <br>
</details>

<details>
  <summary>Multiplication Table - asked by Apple</summary>
    <p>
    <blockquote>
        Suppose you have a multiplication table that is N by N. That is,
        a 2D array where the value at the i-th row and j-th column is (i + 1) * (j + 1) (if 0-indexed) or i * j (if 1-indexed).
        Given integers N and X, write a function that returns the number of times X appears as a value in an N by N multiplication table.
        For example, given N = 6 and X = 12, you should return 4, since the multiplication table looks like this:

        | 1 |  2 |  3 |  4 |  5 |  6 |
        | 2 |  4 |  6 |  8 | 10 | 12 |
        | 3 |  6 |  9 | 12 | 15 | 18 |
        | 4 |  8 | 12 | 16 | 20 | 24 |
        | 5 | 10 | 15 | 20 | 25 | 30 |
        | 6 | 12 | 18 | 24 | 30 | 36 |
</blockquote>
  </p>
  <a href="./multiplicationTable.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-5-multiplication-table-69bea7a60869">explanation</a>
    <br>
    <br>
</details>

<details>
  <summary>Valid parentheses - asked by Google</summary>
    <p>
    <blockquote>
      Given a string of parentheses,
      write a function to compute the minimum number of parentheses to be removed to make the string valid (i.e. each open parenthesis is eventually closed).
      For example, given the string "()())()", you should return 1. Given the string ")(", you should return 2, since we must remove all of them. 
</blockquote>
  </p>
  <a href="./parentheses.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-4-valid-parentheses-aca4214b034b">explanation</a>
    <br>
    <br>
</details>

<details>
  <summary>Division - asked by ContextLogic</summary>
    <p>
      <blockquote>
        Implement division of two positive integers without using the division,
        multiplication, or modulus operators. Return the quotient as an integer,
        ignoring the remainder.
      </blockquote>
    </p>
  <a href="./division.js">solution</a>
  <br>
  explanation
    <br>
    <br>
</details>

<details>
  <summary>Find The largest product - asked by Facebook</summary>
    <p>
      <blockquote>
        Given a list of integers, return the largest product that can be made by multiplying any three integers.
        For example, if the list is [-10, -10, 5, 2], we should return 500, since that's -10 * -10 * 5.
        You can assume the list has at least three integers.
      </blockquote>
    </p>
  <a href="./findTheLargestMultiply.js">solution</a>
  <br>
  <a href="https://medium.com/@obiwankenoobi/interview-question-1-find-the-largest-multiplication-d20aa3723c9d" target="_blank">explanation</a>
    <br>
    <br>
</details>

<details>
  <summary>Create binary tree from sorted array - asked by Cracking the coding intereview</summary>
    <p>
      <blockquote>
        Given a sorted (increasing order) array, write an algorithm to create a binary tree with
        minimal height.
      </blockquote>
    </p>
  <a href="./minimalBinaryTree.js">solution</a>
  <br>
explanation
    <br>
    <br>
</details>


<details>
  <summary>Rotate Image - asked by Cracking the coding intereview</summary>
    <p>
      <blockquote>
        Given an image represented by an NxN matrix,
        write a method to rotate the image by 90 degrees. Can you do this in place?
      </blockquote>
    </p>
  <a href="./rotateImage.js">solution</a>
  <br>
explanation
    <br>
    <br>
</details>




<details>
  <summary>Paint Fill - asked by Cracking the coding intereview</summary>
    <p>
      <blockquote>
        Implement the “paint fill” function that one might see on
        many image editing programs. That is, given a screen
        (represented by a 2 dimensional array of Colors), a point, and a new color,
        fill in the surrounding area until you hit a border of that color.’
      </blockquote>
    </p>
  <a href="./paintFill.js">solution</a>
  <br>
explanation
    <br>
    <br>
</details>



<details>
  <summary>Uniqe String chars - asked by Cracking the coding intereview</summary>
    <p>
      <blockquote>
        Implement an algorithm to determine if a string has all unique characters. What if you
        can not use additional data structures?
      </blockquote>
    </p>
  <a href="./isStringUniqe.js">solution</a>
  <br>
explanation
    <br>
    <br>
</details>

<details>
  <summary>Flat multidimensional array - asked by Facebook (FE position)</summary>
    <p>
      <blockquote>
        Given an array of any types, flat it so it wont have any nested arrays inside
      </blockquote>
    </p>
  <a href="./flattArr.js">solution</a>
  <br>
explanation
    <br>
    <br>
</details>

<details>
  <summary>Decode Message - asked by Facebook (FE position)</summary>
    <p>
      <blockquote>
        Given a grid of characters output a decoded message.
        The message for the following would be IROCLED.
        (diagonally down right and diagonally up right if you can't go further
        .. you continue doing this)

        I B C A L K A
        D R F C A E A
        G H O E L A D
  </blockquote>
  </p>
  <a href="./deCodeString.js">solution</a>
  <br>
explanation
    <br>
    <br>
</details>

<details>
  <summary>Number of Islands - asked by Amazon</summary>
    <p>
      <blockquote>
        Given a matrix of 1s and 0s, return the number of "islands" in the matrix.
        A 1 represents land and 0 represents water,
        so an island is a group of 1s that are neighboring whose perimeter
        is surrounded by water.
        For example, this matrix has 4 islands.

    1 0 0 0 0
    0 0 1 1 0
    0 1 1 0 0
    0 0 0 0 0
    1 1 0 0 1
    1 1 0 0 1
  </p>

   </blockquote>

  <a href="./islands.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-7-find-the-number-of-islands-1216eff9ede9">explanation</a>
    <br>
    <br>
</details>

<details>
  <summary>Bishop Attack - asked by Google</summary>
    <p>
      <blockquote>
  On our special chessboard,
  two bishops attack each other if they share the same diagonal.
  This includes bishops that have another bishop located between them,
  i.e. bishops can attack through pieces.
  You are given N bishops, represented as (row, column)
  tuples on a M by M chessboard.
  Write a function to count the number of pairs of bishops that attack each other.
  The ordering of the pair doesn't matter: (1, 2) is considered the same as (2, 1).
  For example, given M = 5 and the list of bishops:

    (0, 0)
    (1, 2)
    (2, 2)
    (4, 0)

  The board would look like this:

    [b 0 0 0 0]
    [0 0 b 0 0]
    [0 0 b 0 0]
    [0 0 0 0 0]
    [b 0 0 0 0]
  </p>

   </blockquote>

  <a href="./bishopsAttack.js">solution</a>
  <br>
  <a target="_blank" href="https://medium.com/@obiwankenoobi/interview-question-8-bishop-attacks-7780ca7b720">explanation</a>
    <br>
    <br>
</details>


## Data Structures

<details>
  <summary>Binary Search Tree</summary>
    <p>
      <blockquote>
        A binary search tree is a rooted binary tree, whose internal nodes each store a key (and optionally, an associated value) and each have two distinguished sub-trees, commonly denoted left and right. The tree additionally satisfies the binary search property, which states that the key in each node must be greater than or equal to any key stored in the left sub-tree, and less than or equal to any key stored in the right sub-tree.[1]:287 The leaves (final nodes) of the tree contain no key and have no structure to distinguish them from one another. <a href="https://en.wikipedia.org/wiki/Binary_search_tree" target="_blank">wikipedia</a>
      </blockquote>
    </p>
  <a href="./DataStructures/BST/BinarySearchTree.js">solution</a>
  <br>
  <a href="./DataStructures/BST/test.js">test</a>
  <br>
  explanation
    <br>
    <br>
</details>

<details>
  <summary>Linked List</summary>
    <p>
      <blockquote>
        In computer science, a Linked list is a linear collection of data elements, whose order is not given by their physical placement in memory. Instead, each element points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence. In its most basic form, each node contains: data, and a reference (in other words, a link) to the next node in the sequence. This structure allows for efficient insertion or removal of elements from any position in the sequence during iteration. More complex variants add additional links, allowing more efficient insertion or removal of nodes at arbitrary positions. A drawback of linked lists is that access time is linear (and difficult to pipeline). Faster access, such as random access, is not feasible. Arrays have better cache locality compared to linked lists. <a href="https://en.wikipedia.org/wiki/Linked_list" target="_blank">wikipedia</a>
      </blockquote>
    </p>
  <a href="./DataStructures/LinkedList/LinkedList.js">solution</a>
  <br>
  <a href="./DataStructures/LinkedList/test.js">test</a>
  <br>
  explanation
    <br>
    <br>
</details>


<details>
  <summary>Hash Table</summary>
    <p>
      <blockquote>
  In computing, a hash table (hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index into an array of buckets or slots, from which the desired value can be found.

  Ideally, the hash function will assign each key to a unique bucket, but most hash table designs employ an imperfect hash function, which might cause hash collisions where the hash function generates the same index for more than one key. Such collisions must be accommodated in some way.
<a href="https://en.wikipedia.org/wiki/Hash_table" target="_blank">wikipedia</a>
      </blockquote>
    </p>
  <a href="./DataStructures/HashTable/hashTable.js">solution</a>
  <br>
  <a href="./DataStructures/HashTable/test.js">test</a>
  <br>
  explanation
    <br>
    <br>
</details>


<details>
  <summary>Queue</summary>
    <p>
      <blockquote>
    In computer science, a queue is a collection in which the entities in the collection are kept in order and the principal (or only) operations on the collection are the addition of entities to the rear terminal position, known as enqueue, and removal of entities from the front terminal position, known as dequeue. This makes the queue a First-In-First-Out (FIFO) data structure. In a FIFO data structure, the first element added to the queue will be the first one to be removed. This is equivalent to the requirement that once a new element is added, all elements that were added before have to be removed before the new element can be removed. Often a peek or front operation is also entered, returning the value of the front element without dequeuing it. A queue is an example of a linear data structure, or more abstractly a sequential collection.
<a href="https://en.wikipedia.org/wiki/Queue_(abstract_data_type)" target="_blank">wikipedia</a>
      </blockquote>
    </p>
  <a href="./DataStructures/Queue/queue.js">solution</a>
  <br>
  <a href="./DataStructures/Queue/test.js">test</a>
  <br>
  explanation
    <br>
    <br>
</details>