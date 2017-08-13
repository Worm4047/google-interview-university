
## What is it?

This is my multi-month study plan for going from web developer to Google software engineer.

![Coding at the whiteboard - from HBO's Silicon Valley](https://dng5l3qzreal6.cloudfront.net/2016/Aug/coding_board_small-1470866369118.jpg)

This long list has been extracted and expanded from **Google's coaching notes**, so these are the things you need to know.
There are extra items I added at the bottom that may come up in the interview or be helpful in solving a problem. Many items are from
Steve Yegge's "[Get that job at Google](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html)" and are reflected
sometimes word-for-word in Google's coaching notes.

I've pared down what you need to know from what Yegge recommends. I've altered Yegge's requirements 
from information received from my contact at Google. This is meant for **new software engineers** or those switching from 
software/web development to software engineering (where computer science knowledge is required). If you have 
many years of experience and are claiming many years of software engineering experience, expect a harder interview. 
[Read more here](https://googleyasheck.com/what-you-need-to-know-for-your-google-interview-and-what-you-dont/).

If you have many years of software/web development experience, note that Google views software engineering as 
different from software/web development and they require computer science knowledge.

If you want to be a reliability engineer or systems engineer, study more from the optional list (networking, security).

---

## Table of Contents

- [What is it?](#what-is-it)
- [Why use it?](#why-use-it)
- [How to use it](#how-to-use-it)
- [Get in a Googley Mood](#get-in-a-googley-mood)
- [Did I Get the Job?](#did-i-get-the-job)
- [Follow Along with Me](#follow-along-with-me)
- [Don't feel you aren't smart enough](#dont-feel-you-arent-smart-enough)
- [About Google](#about-google)
- [About Video Resources](#about-video-resources)
- [Interview Process & General Interview Prep](#interview-process--general-interview-prep)
- [Pick One Language for the Interview](#pick-one-language-for-the-interview)
- [Book List](#book-list)
- [Before you Get Started](#before-you-get-started)
- [What you Won't See Covered](#what-you-wont-see-covered)
- [Prerequisite Knowledge](#prerequisite-knowledge)
- [The Daily Plan](#the-daily-plan)
- [Algorithmic complexity / Big-O / Asymptotic analysis](#algorithmic-complexity--big-o--asymptotic-analysis)
- [Data Structures](#data-structures)
    - [Arrays](#arrays)
    - [Linked Lists](#linked-lists)
    - [Stack](#stack)
    - [Queue](#queue)
    - [Hash table](#hash-table)
- [More Knowledge](#more-knowledge)
    - [Binary search](#binary-search)
    - [Bitwise operations](#bitwise-operations)
- [Trees](#trees)
    - [Trees - Notes & Background](#trees---notes--background)
    - [Binary search trees: BSTs](#binary-search-trees-bsts)
    - [Heap / Priority Queue / Binary Heap](#heap--priority-queue--binary-heap)
    - balanced search trees (general concept, not details)
    - traversals: preorder, inorder, postorder, BFS, DFS
- [Sorting](#sorting)
    - selection
    - insertion
    - heapsort
    - quicksort
    - merge sort
- [Graphs](#graphs)
    - directed
    - undirected
    - adjacency matrix
    - adjacency list
    - traversals: BFS, DFS
- [Even More Knowledge](#even-more-knowledge)
    - [Recursion](#recursion)
    - [Combinatorics (n choose k) & Probability](#combinatorics-n-choose-k--probability)
    - [NP, NP-Complete and Approximation Algorithms](#np-np-complete-and-approximation-algorithms)
    - [Caches](#caches)
    - [Processes and Threads](#processes-and-threads)
    - [String searching & manipulations](#string-searching--manipulations)
- [System Design, Scalability, Data Handling](#system-design-scalability-data-handling) (if you have 4+ years experience)
- [Final Review](#final-review)
- [Coding Question Practice](#coding-question-practice)
- [Coding exercises/challenges](#coding-exerciseschallenges)
- [Once you're closer to the interview](#once-youre-closer-to-the-interview)
- [Your Resume](#your-resume)
- [Be thinking of for when the interview comes](#be-thinking-of-for-when-the-interview-comes)
- [Have questions for the interviewer](#have-questions-for-the-interviewer)

---------------- Everything below this point is optional ----------------

- [Additional Learning](#additional-learning)
    - [Dynamic Programming](#dynamic-programming)
    - [Compilers](#compilers)
    - [Floating Point Numbers](#floating-point-numbers)
    - [Unicode](#unicode)
    - [Endianness](#endianness)
    - [Unix command line tools](#unix-command-line-tools)
    - [Networking](#networking) (if you have networking experience or want to be a systems engineer, expect questions)
    - [Computer Security](#computer-security)
    - [Garbage collection](#garbage-collection)
    - [Parallel Programming](#parallel-programming)
    - [Tries](#tries)
    - [N-ary (K-ary, M-ary) trees](#n-ary-k-ary-m-ary-trees)
    - [Balanced search trees](#balanced-search-trees)
        - AVL trees
        - Splay trees
        - Red/black trees
        - 2-3 search trees
        - 2-3-4 Trees (aka 2-4 trees)
        - N-ary (K-ary, M-ary) trees
        - B-Trees
    - [k-D Trees](#k-d-trees)
    - [Skip lists](#skip-lists)
    - [Network Flows](#network-flows)
    - [Disjoint Sets & Union Find](#disjoint-sets--union-find)
    - [Math for Fast Processing](#math-for-fast-processing)
    - [Linear Programming](#linear-programming)
    - [Geometry, Convex hull](#geometry-convex-hull)
    - [Discrete math](#discrete-math)

- [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)
- [Video Series](#video-series)


---

## Why use it?

I'm following this plan to prepare for my Google interview. I want to progress into larger systems
and get a real understanding of computer systems, algorithmic efficiency, data structure performance,
low-level languages, and how it all works. And if you don't know any of it, Google won't hire you.

When I started this project, I didn't know a stack from a heap, didn't know Big-O anything, anything about trees, or how to
traverse a graph. If I had to code a sorting algorithm, I can tell ya it wouldn't have been very good.
Every data structure I've ever used was built into the language, and I didn't know how they worked
under the hood at all. I've never had to manage memory unless a process I was running would give an "out of
memory" error, and then I'd have to find a workaround. I've used a few multidimensional arrays in my life and
thousands of associative arrays, but I've never created data structures from scratch.

But after going through this study plan I have high confidence I'll be hired. It's a long plan. It's going to take me months. If you are familiar with a lot of this already it will take you a lot less time.

## Get in a Googley Mood

Print out a "[future Googler](https://github.com/jwasham/google-interview-university/blob/master/extras/future-googler.pdf)" sign (or two) and keep your eyes on the prize.

[![future Googler sign](https://dng5l3qzreal6.cloudfront.net/2016/Oct/Screen_Shot_2016_10_04_at_10_13_24_AM-1475601104364.png)](https://github.com/jwasham/google-interview-university/blob/master/extras/future-googler.pdf)

## Follow Along with Me

My story: [Why I Studied Full-Time for 8 Months for a Google Interview](https://medium.com/@googleyasheck/why-i-studied-full-time-for-8-months-for-a-google-interview-cc662ce9bb13)

I'm on the journey, too.

## Don't feel you aren't smart enough
- Google engineers are smart, but many have an insecurity that they aren't smart enough, even though they work at Google.
- [The myth of the Genius Programmer](https://www.youtube.com/watch?v=0SARbwvhupQ)

## About Google

- [ ] For students - [Google Careers: Technical Development Guide](https://www.google.com/about/careers/students/guide-to-technical-development.html)
- [ ] How Search Works:
    - [x] [The Evolution of Search (video)](https://www.youtube.com/watch?v=mTBShTwCnD4)
    - [ ] [How Search Works - the story](https://www.google.com/insidesearch/howsearchworks/thestory/)
    - [ ] [How Search Works](https://www.google.com/insidesearch/howsearchworks/)
    - [x] [How Search Works - Matt Cutts (video)](https://www.youtube.com/watch?v=BNHR6IQJGZs)
    - [ ] [How Google makes improvements to its search algorithm (video)](https://www.youtube.com/watch?v=J5RZOU6vK4Q)
- [ ] Series:
    - [ ] [How Google Search Dealt With Mobile](https://backchannel.com/how-google-search-dealt-with-mobile-33bc09852dc9)
    - [ ] [Google's Secret Study To Find Out Our Needs](https://backchannel.com/googles-secret-study-to-find-out-our-needs-eba8700263bf)
    - [ ] [Google Search Will Be Your Next Brain](https://backchannel.com/google-search-will-be-your-next-brain-5207c26e4523)
    - [ ] [The Deep Mind Of Demis Hassabis](https://backchannel.com/the-deep-mind-of-demis-hassabis-156112890d8a)
- [ ] [Book: How Google Works](https://www.amazon.com/How-Google-Works-Eric-Schmidt/dp/1455582344)
- [ ] [Made by Google announcement - Oct 2016 (video)](https://www.youtube.com/watch?v=q4y0KOeXViI)

## About Video Resources

Some videos are available only by enrolling in a Coursera, EdX, or Lynda.com class. These are called MOOCs.
Sometimes the classes are not in session so you have to wait a couple of months, so you have no access. Lynda.com courses are not free.

    I'd appreciate your help to add free and always-available public sources, such as YouTube videos to accompany the online course videos.
    I like using university lectures.


## Interview Process & General Interview Prep

- [ ] Videos:
    - [ ] [How to Work at Google: Prepare for an Engineering Interview (video)](https://www.youtube.com/watch?v=ko-KkSmp-Lk)
    - [ ] [How to Work at Google: Example Coding/Engineering Interview (video)](https://www.youtube.com/watch?v=XKu_SEDAykw)
    - [ ] [How to Work at Google - Candidate Coaching Session (video)](https://www.youtube.com/watch?v=oWbUtlUhwa8&feature=youtu.be)
    - [ ] [Google Recruiters Share Technical Interview Tips (video)](https://www.youtube.com/watch?v=qc1owf2-220&feature=youtu.be)
    - [ ] [How to Work at Google: Tech Resume Preparation (video)](https://www.youtube.com/watch?v=8npJLXkcmu8)

- [ ] Articles:
    - [ ] [Becoming a Googler in Three Steps](http://www.google.com/about/careers/lifeatgoogle/hiringprocess/)
    - [ ] [Get That Job at Google](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html)
        - all the things he mentions that you need to know are listed below
    - [ ] _(very dated)_ [How To Get A Job At Google, Interview Questions, Hiring Process](http://dondodge.typepad.com/the_next_big_thing/2010/09/how-to-get-a-job-at-google-interview-questions-hiring-process.html)
    - [ ] [Phone Screen Questions](http://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions)

- [ ] Prep Courses:
    - [ ] [Software Engineer Interview Unleashed (paid course)](https://www.udemy.com/software-engineer-interview-unleashed):
        - Learn how to make yourself ready for software engineer interviews from a former Google interviewer.

- [ ] Additional (not suggested by Google but I added):
    - [ ] [ABC: Always Be Coding](https://medium.com/always-be-coding/abc-always-be-coding-d5f8051afce2#.4heg8zvm4)
    - [ ] [Four Steps To Google Without A Degree](https://medium.com/always-be-coding/four-steps-to-google-without-a-degree-8f381aa6bd5e#.asalo1vfx)
    - [ ] [Whiteboarding](https://medium.com/@dpup/whiteboarding-4df873dbba2e#.hf6jn45g1)
    - [ ] [How Google Thinks About Hiring, Management And Culture](http://www.kpcb.com/blog/lessons-learned-how-google-thinks-about-hiring-management-and-culture)
    - [ ] [Effective Whiteboarding during Programming Interviews](http://www.coderust.com/blog/2014/04/10/effective-whiteboarding-during-programming-interviews/)
    - [ ] Cracking The Coding Interview Set 1:
        - [ ] [Gayle L McDowell - Cracking The Coding Interview (video)](https://www.youtube.com/watch?v=rEJzOhC5ZtQ)
        - [ ] [Cracking the Coding Interview with Author Gayle Laakmann McDowell (video)](https://www.youtube.com/watch?v=aClxtDcdpsQ)
    - [ ] How to Get a Job at the Big 4:
        - [ ] ['How to Get a Job at the Big 4 - Amazon, Facebook, Google & Microsoft' (video)](https://www.youtube.com/watch?v=YJZCUhxNCv8)
    - [ ] [Failing at Google Interviews](http://alexbowe.com/failing-at-google-interviews/)

## Pick One Language for the Interview

I wrote this short article about it: [Important: Pick One Language for the Google Interview](https://googleyasheck.com/important-pick-one-language-for-the-google-interview/)

You can use a language you are comfortable in to do the coding part of the interview, but for Google, these are solid choices:

- C++
- Python

You need to be very comfortable in the language and be knowledgeable.

Read more about choices:
- http://www.byte-by-byte.com/choose-the-right-language-for-your-coding-interview/
- http://blog.codingforinterviews.com/best-programming-language-jobs/
- https://www.quora.com/What-is-the-best-language-to-program-in-for-an-in-person-Google-interview

[See language resources here](programming-language-resources.md)

You'll see some C, C++, and Python learning included below, because I'm learning. There are a few books involved, see the bottom.

## Book List

This is a shorter list than what I used. This is abbreviated to save you time.

### Interview Prep

- [ ] [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - answers in Java
    - recommended on the [Google Careers site](https://www.google.com/about/careers/how-we-hire/interview/)
    - If you see people reference "The Google Resume", it was a book replaced by "Cracking the Coding Interview".

### Computer Architecture

- [ ] [Write Great Code: Volume 1: Understanding the Machine](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
    - The book was published in 2004, and is somehat outdated, but it's a terrific resource for understanding a computer in brief.
    - The author invented HLA, so take mentions and examples in HLA with a grain of salt. Not widely used, but decent examples of what assembly looks like.
    - These chapters are worth the read to give you a nice foundation:
        - Chapter 2 - Numeric Representation
        - Chapter 3 - Binary Arithmetic and Bit Operations
        - Chapter 4 - Floating-Point Representation
        - Chapter 5 - Character Representation
        - Chapter 6 - Memory Organization and Access
        - Chapter 7 - Composite Data Types and Memory Objects
        - Chapter 9 - CPU Architecture
        - Chapter 10 - Instruction Set Architecture
        - Chapter 11 - Memory Architecture and Organization 

### Language Specific

**You need to choose a language for the interview (see above).** Here are my recommendations by language. I don't have resources for all languages. I welcome additions.

If you read though one of these, you should have all the data structures and algorithms knowledge you'll need to start doing coding problems. 
**You can skip all the video lectures in this project**, unless you'd like a review.

[Additional language-specific resources here.](programming-language-resources.md)

### Python

- [ ] [Data Structures and Algorithms in Python](https://www.amazon.com/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275/)

    - Book report: https://googleyasheck.com/book-report-data-structures-and-algorithms-in-python/


## Before you Get Started

### 1. You Won't Remember it All

I watched hours of videos and took copious notes, and months later there was much I didn't remember. I spent 3 days going
through my notes and making flashcards so I could review.

Read please so you won't make my mistakes:

[Retaining Computer Science Knowledge](https://googleyasheck.com/retaining-computer-science-knowledge/)


### 3. Review, review, review

I keep a set of cheat sheets on ASCII, OSI stack, Big-O notations, and more. I study them when I have some spare time.

Take a break from programming problems for a half hour and go through your flashcards.

### 4. Focus

There are a lot of distractions that can take up valuable time. Focus and concentration are hard.

## The Daily Plan

Some subjects take one day, and some will take multiple days. Some are just learning with nothing to implement.

Each day I take one subject from the list below, watch videos about that subject, and write an implementation in:
C++ and Python

Write code on a whiteboard or paper, not a computer. Test with some sample inputs. Then test it out on a computer.

## Prerequisite Knowledge

- [x] **How computers process a program:**
    - [x] [How does CPU execute program (video)](https://www.youtube.com/watch?v=42KTvGYQYnA)
    - [x] [Machine Code Instructions (video)](https://www.youtube.com/watch?v=Mv2XQgpbTNE)

## Algorithmic complexity / Big-O / Asymptotic analysis
- [x] Hired in tech -[Aymptotic section](https://www.hiredintech.com/classrooms/algorithm-design/lesson/48)
- [x] TopCoder (includes recurrence relations and master theorem):
    - [Computational Complexity: Section 1](https://www.topcoder.com/community/data-science/data-science-tutorials/computational-complexity-section-1/)
    - [Computational Complexity: Section 2](https://www.topcoder.com/community/data-science/data-science-tutorials/computational-complexity-section-2/)
- [x] [Cheat sheet](http://bigocheatsheet.com/)

## Data Structures

- ### Arrays
    - [x] [One Dimensional Array](https://www.hackerearth.com/practice/data-structures/arrays/1-d/tutorial/)
    - [x] [Multi Dimensional Array](https://www.hackerearth.com/practice/data-structures/arrays/multi-dimensional/tutorial/)
    - [x] Implement an automatically resizing vector.
    - [x] [Implement a vector](https://github.com/jcapona/data_structures) (mutable array with automatic resizing):
        - [x] Practice coding using arrays and pointers, and pointer math to jump to an index instead of using indexing.
        - [x] new raw data array with allocated memory
            - can allocate int array under the hood, just not use its features
            - start with 16, or if starting number is greater, use power of 2 - 16, 32, 64, 128
        - [x] size() - number of items
        - [x] capacity() - number of items it can hold
        - [x] is_empty()
        - [x] at(index) - returns item at given index, blows up if index out of bounds
        - [x] push(item)
        - [x] insert(index, item) - inserts item at index, shifts that index's value and trailing elements to the right
        - [x] prepend(item) - can use insert above at index 0
        - [x] pop() - remove from end, return value
        - [x] delete(index) - delete item at index, shifting all trailing elements left
        - [x] remove(item) - looks for value and removes index holding it (even if in multiple places)
        - [x] find(item) - looks for value and returns first index with that value, -1 if not found
        - [x] resize(new_capacity) // private function
            - when you reach capacity, resize to double the size
            - when popping an item, if size is 1/4 of capacity, resize to half
    - [x] Time
        - O(1) to add/remove at end (amortized for allocations for more space), index, or update
        - O(n) to insert/remove elsewhere
    - [x] Space
        - contiguous in memory, so proximity helps performance
        - space needed = (array capacity, which is >= n) * size of item, but even if 2n, still O(n)

- ### Linked Lists
    - [x] [Description](http://www.geeksforgeeks.org/linked-list-set-1-introduction/)
    - [x] [Linked List VS Array](http://www.geeksforgeeks.org/linked-list-vs-array/)
    - [x] Operations
        - [Inserting a node](http://www.geeksforgeeks.org/linked-list-set-2-inserting-a-node/)
        - [Deleting a node](http://www.geeksforgeeks.org/linked-list-set-3-deleting-node/)
        - [Deleting node at a given position](http://www.geeksforgeeks.org/delete-a-linked-list-node-at-a-given-position/)
    - [x] [Doubly linked list](http://www.geeksforgeeks.org/doubly-linked-list/)
    - [x] [Circular Linked List](http://www.geeksforgeeks.org/circular-linked-list/)
    - [x] [Circular Linked list traversal](http://geeksquiz.com/circular-linked-list-set-2-traversal/)
    - [x][Programmer's approach to linked list vs array](http://www.geeksforgeeks.org/programmers-approach-looking-array-vs-linked-list/)
    - [x] [why you should avoid linked lists (video)](https://www.youtube.com/watch?v=YQs6IC-vgmo)
 
- ### Stack
    - [x] [Stack Codemonk](https://www.hackerearth.com/practice/data-structures/stacks/basics-of-stacks/tutorial/)
    - [x] [Stack Geeks](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/)
    - [x] [Linked list implementation ](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/)

- ### Queue
    - [x] [Queue Codemonk](https://www.hackerearth.com/practice/data-structures/queues/basics-of-queues/tutorial/)
    - [x] [Queue Intro](http://geeksquiz.com/queue-set-1introduction-and-array-implementation/)
    - [x] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
    - [x] [Priority Queues ](http://www.geeksforgeeks.org/priority-queue-set-1-introduction/)
    - [x] Implement using linked-list, with tail pointer:
        - enqueue(value) - adds value at position at tail
        - dequeue() - returns value and removes least recently added element (front)
        - empty()
    - [x] Implement using fixed-sized array:
        - enqueue(value) - adds item at end of available storage
        - dequeue() - returns value and removes least recently added element
        - empty()
        - full()
    - [x] Cost:
        - a bad implementation using linked list where you enqueue at head and dequeue at tail would be O(n)
            because you'd need the next to last element, causing a full traversal each dequeue
        - enqueue: O(1) (amortized, linked list and array [probing])
        - dequeue: O(1) (linked list and array)
        - empty: O(1) (linked list and array)

- ### Hash table
    - [x] [Hasing DS Intro](http://geeksquiz.com/hashing-set-1-introduction/)
    - [x] [Hashing Codemonk](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/)
    - [] Videos:
        - [x] [Hashing with Chaining Intro](http://geeksquiz.com/hashing-set-2-separate-chaining/)
        - [x] [Hashing with Chaining (video)](https://www.youtube.com/watch?v=0M_kIqhwbFo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=8)
        - [ ] [Table Doubling, Karp-Rabin (video)](https://www.youtube.com/watch?v=BRO7mVIFt08&index=9&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [Open Addr. Intro](http://geeksquiz.com/hashing-set-3-open-addressing/)
        - [ ] [Open Addressing, Cryptographic Hashing (video)](https://www.youtube.com/watch?v=rvdJDijO2Ro&index=10&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [PyCon 2010: The Mighty Dictionary (video)](https://www.youtube.com/watch?v=C4Kc8xzcA68)
        - [ ] [(Advanced) Randomization: Universal & Perfect Hashing (video)](https://www.youtube.com/watch?v=z0lJ2k0sl1g&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=11)
        - [ ] [(Advanced) Perfect hashing (video)](https://www.youtube.com/watch?v=N0COwN14gt0&list=PL2B4EEwhKD-NbwZ4ezj7gyc_3yNrojKM9&index=4)

    - [ ] Online Courses:

        - [ ] [Phone Book Problem (video)](https://www.coursera.org/learn/data-structures/lecture/NYZZP/phone-book-problem)
        - [ ] [Phone book problem](http://www.geeksforgeeks.org/implement-a-phone-directory/)
        - [ ] Distributed hash tables:
            - [Instant Uploads And Storage Optimization In Dropbox (video)](https://www.coursera.org/learn/data-structures/lecture/DvaIb/instant-uploads-and-storage-optimization-in-dropbox)
            - [Distributed Hash Tables (video)](https://www.coursera.org/learn/data-structures/lecture/tvH8H/distributed-hash-tables)

    - [x] Implement with array using linear probing
        - hash(k, m) - m is size of hash table
        - add(key, value) - if key already exists, update value
        - exists(key)
        - get(key)
        - remove(key)

## More Knowledge

- ### Searching
    - [ ] [Linear Search Codemonk](https://www.hackerearth.com/practice/algorithms/searching/linear-search/)
    - [ ] [Binary Search Codemonk](https://www.hackerearth.com/practice/algorithms/searching/binary-search/tutorial/)
    - [ ] [Binary Search (video)](https://www.youtube.com/watch?v=D5SrAga1pno)
    - [ ] [Binary Search (video)](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)
    - [ ] [Detail](https://www.topcoder.com/community/data-science/data-science-tutorials/binary-search/)
    - [ ] Implement:
        - Binary search (on sorted array of integers)
        - Binary search using recursion
    - [ ] Basic Binary search programs
        - Floor of a number in an array.
        - Ceil of number in an array.
        - Finding median of two sorted array.
        - Finding number in a rotated array.
    - [ ] [Ternary Search](https://www.hackerearth.com/practice/algorithms/searching/ternary-search/tutorial/)

- ### Bitwise operations
    - [ ] [Bits cheat sheet](https://github.com/jwasham/google-interview-university/blob/master/extras/cheat%20sheets/bits-cheat-cheet.pdf) - you should know many of the powers of 2 from (2^1 to 2^16 and 2^32)
    - [ ] [Bit Manipulation Codemonk](https://www.hackerearth.com/practice/basic-programming/bit-manipulation/basics-of-bit-manipulation/tutorial/)
    - [ ] Get a really good understanding of manipulating bits with: &, |, ^, ~, >>, <<
        - [ ] [words](https://en.wikipedia.org/wiki/Word_(computer_architecture))
        - [ ] Good intro:
            [Bit Manipulation (video) 30 mins](https://www.youtube.com/watch?v=7jkIUgLC29I)
        - [ ] [C Programming Tutorial 2-10: Bitwise Operators (video)](https://www.youtube.com/watch?v=d0AwjSpNXR0)
        - [ ] [Bithacks](https://graphics.stanford.edu/~seander/bithacks.html)
    - [ ] 2s and 1s complement
        - [Binary: Plusses & Minuses (Why We Use Two's Complement) (video)](https://www.youtube.com/watch?v=lKTsv6iVxV4)
        - [1s Complement](https://en.wikipedia.org/wiki/Ones%27_complement)
        - [2s Complement](https://en.wikipedia.org/wiki/Two%27s_complement)
    - [ ] count set bits
        - [4 ways to count bits in a byte (video)](https://youtu.be/Hzuzo9NJrlc)
        - [Count Bits](https://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan)
        - [How To Count The Number Of Set Bits In a 32 Bit Integer](http://stackoverflow.com/questions/109023/how-to-count-the-number-of-set-bits-in-a-32-bit-integer)
    - [ ] round to next power of 2:
        - [Round Up To Next Power Of Two](http://bits.stephan-brumme.com/roundUpToNextPowerOfTwo.html)
    - [ ] swap values:
        - [Swap](http://bits.stephan-brumme.com/swap.html)
    - [ ] absolute value:
        - [Absolute Integer](http://bits.stephan-brumme.com/absInteger.html)

## Trees

- ### Trees - Notes & Background
    - [ ] [Tree Codemonk](https://www.hackerearth.com/practice/data-structures/trees/binary-and-nary-trees/tutorial/)
    - [ ] [Binary Tree Introduction](http://www.geeksforgeeks.org/binary-tree-set-1-introduction/)
    - [ ] [Binary Tree Properties](http://www.geeksforgeeks.org/binary-tree-set-2-properties/)
    - [ ] [Interesting properties-  Handshaking lemma](http://www.geeksforgeeks.org/handshaking-lemma-and-interesting-tree-properties/)
    - [ ] [Traversal](http://www.geeksforgeeks.org/618/)
    - Manipulation algorithms
    - BFS (breadth-first search)
        - [MIT (video)](https://www.youtube.com/watch?v=s-CYnVz-uh4&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=13)
        - level order (BFS, using queue)
            time complexity: O(n)
            space complexity: best: O(1), worst: O(n/2)=O(n)
    - DFS (depth-first search)
        - [MIT (video)](https://www.youtube.com/watch?v=AfSk24UTFS8&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=14)
        - notes:
            time complexity: O(n)
            space complexity:
                best: O(log n) - avg. height of tree
                worst: O(n)
        - inorder (DFS: left, self, right)
        - postorder (DFS: left, right, self)
        - preorder (DFS: self, left, right)

- ### Binary search trees: BSTs
    - [ ] [Binary Search Tree Review (video) 10 Mins](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
    - [ ] [BST codemonk](https://www.hackerearth.com/practice/data-structures/trees/binary-search-tree/tutorial/)
    - [ ] [BST Sort](http://www.geeksforgeeks.org/tree-sort/)
    - C/C++:
        - [ ] [Binary search tree - Implementation in C/C++ (video)](https://www.youtube.com/watch?v=COZK7NATh4k&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=28)
        - [ ] [BST implementation - memory allocation in stack and heap (video)](https://www.youtube.com/watch?v=hWokyBoo0aI&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=29)
        - [ ] [Find min and max element in a binary search tree (video)](https://www.youtube.com/watch?v=Ut90klNN264&index=30&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Find height of a binary tree (video)](https://www.youtube.com/watch?v=_pnqMz5nrRs&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=31)
        - [ ] [Binary tree traversal - breadth-first and depth-first strategies (video)](https://www.youtube.com/watch?v=9RHO6jU--GU&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=32)
        - [ ] [Binary tree: Level Order Traversal (video)](https://www.youtube.com/watch?v=86g8jAQug04&index=33&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Binary tree traversal: Preorder, Inorder, Postorder (video)](https://www.youtube.com/watch?v=gm8DUJJhmY4&index=34&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Check if a binary tree is binary search tree or not (video)](https://www.youtube.com/watch?v=yEwSGhSsT0U&index=35&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Delete a node from Binary Search Tree (video)](https://www.youtube.com/watch?v=gcULXE7ViZw&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=36)
        - [ ] [Inorder Successor in a binary search tree (video)](https://www.youtube.com/watch?v=5cPbNCrdotA&index=37&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Least common ancestor in bst](http://www.geeksforgeeks.org/lowest-common-ancestor-in-a-binary-search-tree/)
    - [ ] [BST VS HASH](http://www.geeksforgeeks.org/advantages-of-bst-over-hash-table/)
    - [ ] Implement:
        - [ ] insert    // insert value into tree
        - [ ] get_node_count // get count of values stored
        - [ ] print_values // prints the values in the tree, from min to max
        - [ ] delete_tree
        - [ ] is_in_tree // returns true if given value exists in the tree
        - [ ] get_height // returns the height in nodes (single node's height is 1)
        - [ ] get_min   // returns the minimum value stored in the tree
        - [ ] get_max   // returns the maximum value stored in the tree
        - [ ] is_binary_search_tree
        - [ ] delete_value
        - [ ] get_successor // returns next-highest value in tree after given value, -1 if none

- ### Heap / Priority Queue / Binary Heap
    - visualized as a tree, but is usually linear in storage (array, linked list)
    - [ ] [Heap Codemonk](https://www.hackerearth.com/practice/data-structures/trees/heapspriority-queues/)
    - [ ] [Introduction (video) 6 min](https://www.coursera.org/learn/data-structures/lecture/2OpTs/introduction)
    - [ ] Types of Heap
        - [ ] [Binary Heap](http://geeksquiz.com/binary-heap/)
        - [ ] [Binomial Heap](http://www.geeksforgeeks.org/binomial-heap-2/)
        - [ ] [Fibonacci Heap](http://www.geeksforgeeks.org/fibonacci-heap-set-1-introduction/)
    - [ ] [Adv. of Heap over BST as Priority queue](http://www.geeksforgeeks.org/why-is-binary-heap-preferred-over-bst-for-priority-queue/)
    - [ ] [Naive Implementations (video)](https://www.coursera.org/learn/data-structures/lecture/z3l9N/naive-implementations)
    - [ ] [Pseudocode (video)](https://www.coursera.org/learn/data-structures/lecture/HxQo9/pseudocode)
    - [ ] [Heap Sort] (https://www.hackerearth.com/practice/notes/heaps-and-priority-queues/)
    - [ ] [CS 61B Lecture 24: Priority Queues (video)](https://www.youtube.com/watch?v=yIUFT6AKBGE&index=24&list=PL4BBB74C7D2A1049C)
    - [ ] [Linear Time BuildHeap (max-heap)](https://www.youtube.com/watch?v=MiyLo8adrWw)
    - [ ] Implement a max-heap:
        - [ ] insert
        - [ ] sift_up - needed for insert
        - [ ] get_max - returns the max item, without removing it
        - [ ] get_size() - return number of elements stored
        - [ ] is_empty() - returns true if heap contains no elements
        - [ ] extract_max - returns the max item, removing it
        - [ ] sift_down - needed for extract_max
        - [ ] remove(i) - removes item at index x
        - [ ] heapify - create a heap from an array of elements, needed for heap_sort
        - [ ] heap_sort() - take an unsorted array and turn it into a sorted array in-place using a max heap
            - note: using a min heap instead would save operations, but double the space needed (cannot do in-place).
    - [ ] [Nearly sorted algorithm](http://www.geeksforgeeks.org/nearly-sorted-algorithm/)

## Sorting

- [ ] Notes:
    - Implement sorts & know best case/worst case, average complexity of each:
        - no bubble sort - it's terrible - O(n^2), except when n <= 16
    - [ ] Stability in sorting algorithms ("Is Quicksort stable?")
        - [Stability In Sorting Algorithms](http://www.geeksforgeeks.org/stability-in-sorting-algorithms/)
    - [ ] Which algorithms can be used on linked lists? Which on arrays? Which on both?
        - I wouldn't recommend sorting a linked list, but merge sort is doable.
        - [Merge Sort For Linked List](http://www.geeksforgeeks.org/merge-sort-for-linked-list/)
    - [ ] [Topcoder tutorial on sorting](https://www.topcoder.com/community/data-science/data-science-tutorials/sorting/)

- For heapsort, see Heap data structure above. Heap sort is great, but not stable.

- [ ] [Sedgewick - Mergesort (5 videos)](https://www.youtube.com/watch?v=4nKwesx_c8E&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [1. Mergesort](https://www.youtube.com/watch?v=4nKwesx_c8E&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9&index=1)
    - [ ] [2. Bottom up Mergesort](https://www.youtube.com/watch?v=HGOIGUYjeyk&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9&index=2)
    - [ ] [3. Sorting Complexity](https://www.youtube.com/watch?v=WvU_mIWo0Ac&index=3&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [4. Comparators](https://www.youtube.com/watch?v=7MvC1kmBza0&index=4&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [5. Stability](https://www.youtube.com/watch?v=XD_5iINB5GI&index=5&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [MergeSort codemonk](https://www.hackerearth.com/practice/algorithms/sorting/merge-sort/tutorial/)

- [ ] [Sedgewick - Quicksort (4 videos)](https://www.youtube.com/playlist?list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [1. Quicksort](https://www.youtube.com/watch?v=5M5A7qPWk84&index=1&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [2. Selection](https://www.youtube.com/watch?v=CgVYfSyct_M&index=2&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [3. Duplicate Keys](https://www.youtube.com/watch?v=WBFzOYJ5ybM&index=3&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [4. System Sorts](https://www.youtube.com/watch?v=rejpZ2htBjE&index=4&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [QuickSort](https://www.hackerearth.com/practice/algorithms/sorting/quick-sort/tutorial/)

- [ ] [BubbleSort Codemonk](https://www.hackerearth.com/practice/algorithms/sorting/bubble-sort/tutorial/)
- [ ] [Insertion Sort Codemonk](https://www.hackerearth.com/practice/algorithms/sorting/insertion-sort/tutorial/)
- [ ] [Selection Sort Codemonk](https://www.hackerearth.com/practice/algorithms/sorting/selection-sort/tutorial/)

- [ ] Implement:
    - [ ] Mergesort: O(n log n) average and worst case
    - [ ] Quicksort O(n log n) average case
    - Selection sort and insertion sort are both O(n^2) average and worst case
    - For heapsort, see Heap data structure above.

- [ ] Not required, but I recommended them:
    - [ ] [Sedgewick - Radix Sorts (6 videos)](https://www.youtube.com/playlist?list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
        - [ ] [2. Key Indexed Counting](https://www.youtube.com/watch?v=CtgKYmXs62w&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=5)
        - [ ] [3. Least Significant Digit First String Radix Sort](https://www.youtube.com/watch?v=2pGVq_BwPKs&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=4)
        - [ ] [4. Most Significant Digit First String Radix Sort](https://www.youtube.com/watch?v=M3cYNY90R6c&index=3&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
        - [ ] [5. 3 Way Radix Quicksort](https://www.youtube.com/watch?v=YVl58kfE6i8&index=2&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
        - [ ] [6. Suffix Arrays](https://www.youtube.com/watch?v=HKPrVm5FWvg&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=1)
    - [ ] [Radix Sort Codemonk](https://www.hackerearth.com/practice/algorithms/sorting/radix-sort/tutorial/)
    - [ ] [Counting Sort Codemonk](https://www.hackerearth.com/practice/algorithms/sorting/counting-sort/tutorial/)
    - [ ] [Radix Sort, Counting Sort (linear time given constraints) (video)](https://www.youtube.com/watch?v=Nz1KZXbghj8&index=7&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [Randomization: Matrix Multiply, Quicksort, Freivalds' algorithm (video)](https://www.youtube.com/watch?v=cNB2lADK3_s&index=8&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [Sorting in Linear Time (video)](https://www.youtube.com/watch?v=pOKy3RZbSws&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=14)

## Graphs

Graphs can be used to represent many problems in computer science, so this section is long, like trees and sorting were.

- Notes from Yegge:
    - There are three basic ways to represent a graph in memory:
        - Objects and pointers.
        - Matrix.
        - Adjacency list.
    - Familiarize yourself with each representation and its pros & cons
    - BFS and DFS - know their computational complexity, their tradeoffs, and how to implement them in real code
    - When asked a question, look for a graph-based solution first, then move on if none.

- [ ] Skiena Lectures - great intro:
    - [ ] [CSE373 2012 - Lecture 11 - Graph Data Structures (video)](https://www.youtube.com/watch?v=OiXxhDrFruw&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=11)
    - [ ] [CSE373 2012 - Lecture 12 - Breadth-First Search (video)](https://www.youtube.com/watch?v=g5vF8jscteo&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=12)
    - [ ] [CSE373 2012 - Lecture 13 - Graph Algorithms (video)](https://www.youtube.com/watch?v=S23W6eTcqdY&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=13)
    - [ ] [CSE373 2012 - Lecture 14 - Graph Algorithms (con't) (video)](https://www.youtube.com/watch?v=WitPBKGV0HY&index=14&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [ ] [CSE373 2012 - Lecture 15 - Graph Algorithms (con't 2) (video)](https://www.youtube.com/watch?v=ia1L30l7OIg&index=15&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [ ] [CSE373 2012 - Lecture 16 - Graph Algorithms (con't 3) (video)](https://www.youtube.com/watch?v=jgDOQq6iWy8&index=16&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)

- [ ] Graphs (review and more):

    - [ ] [6.006 Single-Source Shortest Paths Problem (video)](https://www.youtube.com/watch?v=Aa2sqUhIn-E&index=15&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.006 Dijkstra (video)](https://www.youtube.com/watch?v=2E7MmKv0Y24&index=16&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.006 Bellman-Ford (video)](https://www.youtube.com/watch?v=ozsuci5pIso&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=17)
    - [ ] [6.006 Speeding Up Dijkstra (video)](https://www.youtube.com/watch?v=CHvQ3q_gJ7E&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=18)
    - [ ] [Aduni: Graph Algorithms I - Topological Sorting, Minimum Spanning Trees, Prim's Algorithm -  Lecture 6 (video)]( https://www.youtube.com/watch?v=i_AQT_XfvD8&index=6&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [ ] [Aduni: Graph Algorithms II - DFS, BFS, Kruskal's Algorithm, Union Find Data Structure - Lecture 7 (video)]( https://www.youtube.com/watch?v=ufj5_bppBsA&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=7)
    - [ ] [Aduni: Graph Algorithms III: Shortest Path - Lecture 8 (video)](https://www.youtube.com/watch?v=DiedsPsMKXc&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=8)
    - [ ] [Aduni: Graph Alg. IV: Intro to geometric algorithms - Lecture 9 (video)](https://www.youtube.com/watch?v=XIAQRlNkJAw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=9)
    - [ ] [CS 61B 2014 (starting at 58:09) (video)](https://youtu.be/dgjX4HdMI-Q?list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&t=3489)
    - [ ] [CS 61B 2014: Weighted graphs (video)](https://www.youtube.com/watch?v=aJjlQCFwylA&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=19)
    - [ ] [Greedy Algorithms: Minimum Spanning Tree (video)](https://www.youtube.com/watch?v=tKwnms5iRBU&index=16&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [Strongly Connected Components Kosaraju's Algorithm Graph Algorithm (video)](https://www.youtube.com/watch?v=RpgcYiky7uw)

- To implement:
    - [ ] DFS with adjacency list (recursive)
    - [ ] DFS with adjacency list (iterative with stack)
    - [ ] DFS with adjacency matrix (recursive)
    - [ ] DFS with adjacency matrix (iterative with stack)
    - [ ] BFS with adjacency list
    - [ ] BFS with adjacency matrix
    - [ ] single-source shortest path (Dijkstra)
    - [ ] minimum spanning tree
    - DFS-based algorithms (see Aduni videos above):
        - [ ] check for cycle (needed for topological sort, since we'll check for cycle before starting)
        - [ ] topological sort
        - [ ] count connected components in a graph
        - [ ] list strongly connected components
        - [ ] check for bipartite graph

- ### String searching & manipulations
    - [ ] [Sedgewick - Suffix Arrays (video)](https://www.youtube.com/watch?v=HKPrVm5FWvg)
    - [ ] [Sedgewick - Substring Search (videos)](https://www.youtube.com/watch?v=2LvvVFCEIv8&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=5)
        - [ ] [1. Introduction to Substring Search](https://www.youtube.com/watch?v=2LvvVFCEIv8&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=5)
        - [ ] [2. Brute-Force Substring Search](https://www.youtube.com/watch?v=CcDXwIGEXYU&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=4)
        - [ ] [3. Knuth-Morris Pratt](https://www.youtube.com/watch?v=n-7n-FDEWzc&index=3&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66)
        - [ ] [4. Boyer-Moore](https://www.youtube.com/watch?v=fI7Ch6pZXfM&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=2)
        - [ ] [5. Rabin-Karp](https://www.youtube.com/watch?v=QzI0p6zDjK4&index=1&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66)
    - [ ] [Search pattern in text (video)](https://www.coursera.org/learn/data-structures/lecture/tAfHI/search-pattern-in-text)
    - [ ] Strings in Python
        - [ ] [Set 1](http://www.geeksforgeeks.org/interesting-facts-about-strings-in-python-set-1/)
        - [ ] [Set 2](http://www.geeksforgeeks.org/interesting-facts-about-strings-in-python-set-2/)
    - [ ] Strings method in python
        - [ ] [Set 1](http://www.geeksforgeeks.org/string-methods-python-set-1/)
        - [ ] [Set 2](http://www.geeksforgeeks.org/string-methods-python-set-2/)
        - [ ] [Set 3](http://www.geeksforgeeks.org/string-methods-python-set-3/)

- ### Recursion
    - [ ] Stanford lectures on recursion & backtracking:
        - [ ] [Lecture 8 | Programming Abstractions (video)](https://www.youtube.com/watch?v=gl3emqCuueQ&list=PLFE6E58F856038C69&index=8)
        - [ ] [Lecture 9 | Programming Abstractions (video)](https://www.youtube.com/watch?v=uFJhEPrbycQ&list=PLFE6E58F856038C69&index=9)
        - [ ] [Lecture 10 | Programming Abstractions (video)](https://www.youtube.com/watch?v=NdF1QDTRkck&index=10&list=PLFE6E58F856038C69)
        - [ ] [Lecture 11 | Programming Abstractions (video)](https://www.youtube.com/watch?v=p-gpaIGRCQI&list=PLFE6E58F856038C69&index=11)
    - when it is appropriate to use it
    - how is tail recursion better than not?
        - [ ] [What Is Tail Recursion Why Is It So Bad?](https://www.quora.com/What-is-tail-recursion-Why-is-it-so-bad)
        - [ ] [Tail Recursion (video)](https://www.youtube.com/watch?v=L1jjXGfxozc)

- ### Combinatorics (n choose k) & Probability
    - [ ] [Make School: More Probability and Markov Chains (video)](https://www.youtube.com/watch?v=dNaJg-mLobQ)
    - [ ] Khan Academy:
        - Course layout:
            - [ ] [Basic Theoretical Probability](https://www.khanacademy.org/math/probability/probability-and-combinatorics-topic)
        - Just the videos - 41 (each are simple and each are short):
            - [ ] [Probability Explained (video)](https://www.youtube.com/watch?v=uzkc-qNVoOk&list=PLC58778F28211FA19)
            
## Even More Knowledge
- ### NP, NP-Complete and Approximation Algorithms
    - Know about the most famous classes of NP-complete problems, such as traveling salesman and the knapsack problem,
        and be able to recognize them when an interviewer asks you them in disguise.
    - Know what NP-complete means.

    - [ ] [Computational Complexity (video)](https://www.youtube.com/watch?v=moPtwq_cVH8&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=23)

    - [ ] Skiena:

        - [ ] [CSE373 2012 - Lecture 24 - NP-Completeness Proofs (video)](https://www.youtube.com/watch?v=27Al52X3hd4&index=24&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
        - [ ] [CSE373 2012 - Lecture 25 - NP-Completeness Challenge (video)](https://www.youtube.com/watch?v=xCPH4gwIIXM&index=25&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [ ] [Complexity: P, NP, NP-completeness, Reductions (video)](https://www.youtube.com/watch?v=eHZifpgyH_4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=22)
    - [ ] [Complexity: Approximation Algorithms (video)](https://www.youtube.com/watch?v=MEz1J9wY2iM&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=24)
    - [ ] [Complexity: Fixed-Parameter Algorithms (video)](https://www.youtube.com/watch?v=4q-jmGrmxKs&index=25&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - Pages 1048 - 1140 in CLRS if you have it.

- ### Dynamic Programming
    - [Dynamic Programming – From Novice to Advanced](https://www.topcoder.com/community/data-science/data-science-tutorials/dynamic-programming-from-novice-to-advanced/)
    - [ ][Overview](https://www.hiredintech.com/classrooms/algorithm-design/lesson/11)
    - [ ] Videos:
        - [ ] List of individual DP problems (each is short):
            [Dynamic Programming (video)](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)
    - [ ] Yale Lecture notes:
        - [ ] [Dynamic Programming](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#dynamicProgramming)
    - [ ] [Practise](http://www.geeksforgeeks.org/dynamic-programming/):

Supplemental:

- [Number Theory 1](https://www.hackerearth.com/practice/math/number-theory/basic-number-theory-1/tutorial/)
- [Number Theory 2](https://www.hackerearth.com/practice/math/number-theory/basic-number-theory-2/tutorial/)
- [Mathematics for Topcoders](https://www.topcoder.com/community/data-science/data-science-tutorials/mathematics-for-topcoders/)

- [MIT Interview Materials](https://web.archive.org/web/20160906124824/http://courses.csail.mit.edu/iap/interview/materials.php)
- [Exercises for getting better at a given language](http://exercism.io/languages)

Beyond Supplemental
- ### Tries
    - Note there are different kinds of tries. Some have prefixes, some don't, and some use string instead of bits to track the path.
    - [ ] [TopCoder - Using Tries](https://www.topcoder.com/community/data-science/data-science-tutorials/using-tries/)
    - [ ] [Sedgewick - Tries (3 videos)](https://www.youtube.com/playlist?list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
        - [ ] [1. R Way Tries](https://www.youtube.com/watch?v=buq2bn8x3Vo&index=3&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
        - [ ] [2. Ternary Search Tries](https://www.youtube.com/watch?v=LelV-kkYMIg&index=2&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
        - [ ] [3. Character Based Operations](https://www.youtube.com/watch?v=00YaFPcC65g&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ&index=1)

- ### Balanced search trees
    - Know least one type of balanced binary tree (and know how it's implemented):
    - "Among balanced search trees, AVL and 2/3 trees are now passé, and red-black trees seem to be more popular.
        A particularly interesting self-organizing data structure is the splay tree, which uses rotations
        to move any accessed key to the root." - Skiena
    - Of these, I chose to implement a splay tree. From what I've read, you won't implement a
        balanced search tree in your interview. But I wanted exposure to coding one up
        and let's face it, splay trees are the bee's knees. I did read a lot of red-black tree code.
        - splay tree: insert, search, delete functions
        If you end up implementing red/black tree try just these:
        - search and insertion functions, skipping delete
    - I want to learn more about B-Tree since it's used so widely with very large data sets.
    - [ ] [Self-balancing binary search tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)

    - [ ] **AVL trees**
        - In practice:
            From what I can tell, these aren't used much in practice, but I could see where they would be:
            The AVL tree is another structure supporting O(log n) search, insertion, and removal. It is more rigidly
            balanced than red–black trees, leading to slower insertion and removal but faster retrieval. This makes it
            attractive for data structures that may be built once and loaded without reconstruction, such as language
            dictionaries (or program dictionaries, such as the opcodes of an assembler or interpreter).
        - [ ] [MIT AVL Trees / AVL Sort (video)](https://www.youtube.com/watch?v=FNeL18KsWPc&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=6)
        - [ ] [AVL Trees (video)](https://www.coursera.org/learn/data-structures/lecture/Qq5E0/avl-trees)
        - [ ] [AVL Tree Implementation (video)](https://www.coursera.org/learn/data-structures/lecture/PKEBC/avl-tree-implementation)
        - [ ] [Split And Merge](https://www.coursera.org/learn/data-structures/lecture/22BgE/split-and-merge)

    - [ ] **Splay trees**
        - In practice:
            Splay trees are typically used in the implementation of caches, memory allocators, routers, garbage collectors,
            data compression, ropes (replacement of string used for long text strings), in Windows NT (in the virtual memory,
            networking and file system code) etc.
        - [ ] [CS 61B: Splay Trees (video)](https://www.youtube.com/watch?v=Najzh1rYQTo&index=23&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd)
        - [ ] MIT Lecture: Splay Trees:
            - Gets very mathy, but watch the last 10 minutes for sure.
            - [Video](https://www.youtube.com/watch?v=QnPl_Y6EqMo)

    - [ ] **Red/black trees**
        - these are a translation of a 2-3 tree (see below)
        - In practice:
            Red–black trees offer worst-case guarantees for insertion time, deletion time, and search time.
            Not only does this make them valuable in time-sensitive applications such as real-time applications,
            but it makes them valuable building blocks in other data structures which provide worst-case guarantees;
            for example, many data structures used in computational geometry can be based on red–black trees, and
            the Completely Fair Scheduler used in current Linux kernels uses red–black trees. In the version 8 of Java,
            the Collection HashMap has been modified such that instead of using a LinkedList to store identical elements with poor
            hashcodes, a Red-Black tree is used.
        - [ ] [Aduni - Algorithms - Lecture 4 (link jumps to starting point) (video)](https://youtu.be/1W3x0f_RmUo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3871)
        - [ ] [Aduni - Algorithms - Lecture 5 (video)](https://www.youtube.com/watch?v=hm2GHwyKF1o&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=5)
        - [ ] [Black Tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)
        - [ ] [An Introduction To Binary Search And Red Black Tree](https://www.topcoder.com/community/data-science/data-science-tutorials/an-introduction-to-binary-search-and-red-black-trees/)

    - [ ] **2-3 search trees**
        - In practice:
            2-3 trees have faster inserts at the expense of slower searches (since height is more compared to AVL trees).
        - You would use 2-3 tree very rarely because its implementation involves different types of nodes. Instead, people use Red Black trees.
        - [ ] [23-Tree Intuition and Definition (video)](https://www.youtube.com/watch?v=C3SsdUqasD4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=2)
        - [ ] [Binary View of 23-Tree](https://www.youtube.com/watch?v=iYvBtGKsqSg&index=3&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [2-3 Trees (student recitation) (video)](https://www.youtube.com/watch?v=TOb1tuEZ2X4&index=5&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

    - [ ] **N-ary (K-ary, M-ary) trees**
        - note: the N or K is the branching factor (max branches)
        - binary trees are a 2-ary tree, with branching factor = 2
        - 2-3 trees are 3-ary
        - [ ] [K-Ary Tree](https://en.wikipedia.org/wiki/K-ary_tree)

    - [ ] **B-Trees**
        - fun fact: it's a mystery, but the B could stand for Boeing, Balanced, or Bayer (co-inventor)
        - In Practice:
            B-Trees are widely used in databases. Most modern filesystems use B-trees (or Variants). In addition to
            its use in databases, the B-tree is also used in filesystems to allow quick random access to an arbitrary
            block in a particular file. The basic problem is turning the file block i address into a disk block
            (or perhaps to a cylinder-head-sector) address.
        - [ ] [B-Tree](https://en.wikipedia.org/wiki/B-tree)
        - [ ] [Introduction to B-Trees (video)](https://www.youtube.com/watch?v=I22wEC1tTGo&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=6)
        - [ ] [B-Tree Definition and Insertion (video)](https://www.youtube.com/watch?v=s3bCdZGrgpA&index=7&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [B-Tree Deletion (video)](https://www.youtube.com/watch?v=svfnVhJOfMc&index=8&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [MIT 6.851 - Memory Hierarchy Models (video)](https://www.youtube.com/watch?v=V3omVLzI0WE&index=7&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf)
                - covers cache-oblivious B-Trees, very interesting data structures
                - the first 37 minutes are very technical, may be skipped (B is block size, cache line size)

- ### Network Flows
    - [ ] [Ford-Fulkerson in 5 minutes (video)](https://www.youtube.com/watch?v=v1VgJmkEJW0)
    - [ ] [Ford-Fulkerson Algorithm (video)](https://www.youtube.com/watch?v=v1VgJmkEJW0)
    - [ ] [Network Flows (video)](https://www.youtube.com/watch?v=2vhN4Ice5jI)

- ### Disjoint Sets & Union Find
    - [ ] [UCB 61B - Disjoint Sets; Sorting & selection (video)](https://www.youtube.com/watch?v=MAEGXTwmUsI&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=21)
    - [ ] [Sedgewick Algorithms - Union-Find (6 videos)](https://www.youtube.com/watch?v=8mYfZeHtdNc&list=PLe-ggMe31CTexoNYnMhbHaWhQ0dvcy43t)

- ### Math for Fast Processing
    - [ ] [Integer Arithmetic, Karatsuba Multiplication (video)](https://www.youtube.com/watch?v=eCaXlAaN2uE&index=11&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [The Chinese Remainder Theorem (used in cryptography) (video)](https://www.youtube.com/watch?v=ru7mWZJlRQg)

- ### Linear Programming (videos)
    - [ ] [Linear Programming](https://www.youtube.com/watch?v=M4K6HYLHREQ)
    - [ ] [Finding minimum cost](https://www.youtube.com/watch?v=2ACJ9ewUC6U)
    - [ ] [Finding maximum value](https://www.youtube.com/watch?v=8AA_81xI3ik)
    - [ ] [Solve Linear Equations with Python - Simplex Algorithm](https://www.youtube.com/watch?v=44pAWI7v5Zk)

- ### Geometry, Convex hull (videos)
    - [ ] [Graph Alg. IV: Intro to geometric algorithms - Lecture 9](https://youtu.be/XIAQRlNkJAw?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3164)
    - [ ] [Geometric Algorithms: Graham & Jarvis - Lecture 10](https://www.youtube.com/watch?v=J5aJEcOr6Eo&index=10&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [ ] [Divide & Conquer: Convex Hull, Median Finding](https://www.youtube.com/watch?v=EzeYI7p9MjU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=2)

## Coding Question Practice

Now that you know all the computer science topics above, it's time to practice answering coding problems.

**Coding question practice is not about memorizing answers to programming problems.**

Why you need to practice doing programming problems:
- problem recognition, and where the right data structures and algorithms fit in
- gathering requirements for the problem
- talking your way through the problem like you will in the interview
- coding on a whiteboard or paper, not a computer
- coming up with time and space complexity for your solutions
- testing your solutions

There is a great intro for methodical, communicative problem solving in an interview. You'll get this from the programming
interview books, too, but I found this outstanding:
[Algorithm design canvas](http://www.hiredintech.com/algorithm-design/)

[My Process for Coding Interview (Book) Exercises](https://googleyasheck.com/my-process-for-coding-interview-exercises/)

No whiteboard at home? That makes sense. I'm a weirdo and have a big whiteboard. Instead of a whiteboard, pick up a
large drawing pad from an art store. You can sit on the couch and practice. This is my "sofa whiteboard".
I added the pen in the photo for scale. If you use a pen, you'll wish you could erase. Gets messy quick.

![my sofa whiteboard](https://dng5l3qzreal6.cloudfront.net/2016/Oct/art_board_sm_2-1476233630368.jpg)

**Read and Do Programming Problems (in this order):**

- [ ] [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - answers in Java

See [Book List above](#book-list)

## Coding exercises/challenges

Once you've learned your brains out, put those brains to work.
Take coding challenges every day, as many as you can.

- [ ] [How to Find a Solution](https://www.topcoder.com/community/data-science/data-science-tutorials/how-to-find-a-solution/)
- [ ] [How to Dissect a Topcoder Problem Statement](https://www.topcoder.com/community/data-science/data-science-tutorials/how-to-dissect-a-topcoder-problem-statement/)

Challenge sites:
- [LeetCode](https://leetcode.com/)
- [TopCoder](https://www.topcoder.com/)
- [Project Euler (math-focused)](https://projecteuler.net/index.php?section=problems)
- [HackerRank](https://www.hackerrank.com/)
- [Geeks for Geeks](http://www.geeksforgeeks.org/)
- [InterviewBit](https://www.interviewbit.com/invite/icjf)

Maybe:
- [Mock interviewers from big companies](http://www.gainlo.co/)

## Once you're closer to the interview

- [ ] Cracking The Coding Interview Set 2 (videos):
    - [Cracking The Code Interview](https://www.youtube.com/watch?v=4NIb9l3imAo)
    - [Cracking the Coding Interview - Fullstack Speaker Series](https://www.youtube.com/watch?v=Eg5-tdAwclo)
    - [Ask Me Anything: Gayle Laakmann McDowell (author of Cracking the Coding Interview)](https://www.youtube.com/watch?v=1fqxMuPmGak)

## Your Resume

- [Ten Tips for a (Slightly) Less Awful Resume](http://steve-yegge.blogspot.co.uk/2007_09_01_archive.html)
- See Resume prep items in Cracking The Coding Interview and back of Programming Interviews Exposed


## Be thinking of for when the interview comes

Think of about 20 interview questions you'll get, along with the lines of the items below. Have 2-3 answers for each.
Have a story, not just data, about something you accomplished.

- Why do you want this job?
- What's a tough problem you've solved?
- Biggest challenges faced?
- Best/worst designs seen?
- Ideas for improving an existing Google product.
- How do you work best, as an individual and as part of a team?
- Which of your skills or experiences would be assets in the role and why?
- What did you most enjoy at [job x / project y]?
- What was the biggest challenge you faced at [job x / project y]?
- What was the hardest bug you faced at [job x / project y]?
- What did you learn at [job x / project y]?
- What would you have done better at [job x / project y]?

## Have questions for the interviewer

    Some of mine (I already may know answer to but want their opinion or team perspective):

- How large is your team?
- What does your dev cycle look like? Do you do waterfall/sprints/agile?
- Are rushes to deadlines common? Or is there flexibility?
- How are decisions made in your team?
- How many meetings do you have per week?
- Do you feel your work environment helps you concentrate?
- What are you working on?
- What do you like about it?
- What is the work life like?

---

    *****************************************************************************************************
    *****************************************************************************************************

    Everything below this point is optional.
    By studying these, you'll get greater exposure to more CS concepts, and will be better prepared for
    any software engineering job. You'll be a much more well-rounded software engineer.

    *****************************************************************************************************
    *****************************************************************************************************

---

