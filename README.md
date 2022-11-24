# Resource Hub
A place to store and consolidate resources that are helpful for learning and coding. 

This is meant for a marginally more organized means of storing resources rather than random bookmarks. If you like it then please give it a star :smiley:

## Data Structures and Algorithms
Data structures and algorithms are a bit of a meme but are still part of the song and dance we need to go through. 

### Learning the fundamentals
A great way to actually start to wrap your head around what is going on 
is <a href="https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/pages/syllabus/">this course by MIT.</a> 
It does assume some mathematical knowledge but you don't need to understand all the maths to learn the content but it will be helpful to understand
the why. That being said, you need to have a firm grasp on Big O notation, why it's important and how to get the Big O for code you write. 

### Practicing the DSA
#### Leetcode
Learning about DSA is one thing but there is nothing like implementing them to really wrap your head around it. 
A great example of this is <a href="www.leetcode.com">leetcode</a>. Look at the very first problem,
<a href="https://leetcode.com/problems/two-sum/">Two Sum<a>. It's conceptually easy to solve with a nested loop but you will most likely
not pass the test and get a "Time Limit Exceeded" error as this is an $O(n^2)$ solution. A less obvious solution that runs in $O(n)$ 
utilizes a hashmap. Doing these problems will help you understand when to make comprimises when coding your own projects. Is runtime speed more
valuable than code complexity? Can you achieve both?

#### Neetcode
While Leetcode is an en excellent resource, it is unstructured. I've found a lot of benefit by going through structured lists like 
<a href="https://neetcode.io/practice">Neetcode</a> which provides Leetcode questions grouped by topic. 
Each problem comes with a video solution. I'd recommend doing a deep dive into each topic until you're familiar with it before moving on to another topic

#### Other resources
There are other structured resources that try to group relevant questions DSA questions and resources such as:
- <a href="https://alphabet150.com/">Alphebet 150</a> which tries to group popular Google problems together
- <a href="https://leetcode.com/discuss/general-discussion/494279/comprehensive-data-structure-and-algorithm-study-guide">DSA study guide by xrssa</a> which provides a host of other resources to learn from
- <a href="https://www.crackingthecodinginterview.com/">Cracking the Coding Interview - CTCI</a> is a great book to guide you in DSA as well as other interview prep. This book often is claimed to be "too easy" or "dated" and that may be true is considering the difficulty level but it does teach the foundational elements well 
- <a href="https://github.com/hiAndrewQuinn/LeetCode-Anki">Leetcode Anki</a> is a great system to turn your leetcode solutions into flashcards so you can study on the go. You do need an Anki account which I'd recommend anyway 

## System Design
What's the point in knowing how to code a small standalone program if you don't know how to integrate all components together to create a product?
This is where system design comes in, an ELI5 explanation would be how to get your business logic, databases and users to interact as a cohesive whole

An excellent point to start is <a href="https://github.com/karanpratapsingh/system-design">here</a>. Another github repo where someone has
consolidated many resources together


## Employment
Generally a thing most of us require is money, which we mostly get from employment. One of the issues in tech is that many companies do not advertise 
on common job boards such as seek as they would get flooded with results. 

### General
- <a href='linkedin.com'>LinkedIn</a> - referrals are king, recruiters will reach out to you if you are desirable

### Australia focused
- <a href='https://matchstiq.io/'>matchstiq</a> focuses on startups
- <a href='https://www.ribit.net/'>ribit</a> focuses on students, internships and graduate positions 
- <a href='https://jobs.blackbird.vc/jobs'>blackbird.vc</a>
- <a href='https://jobs.airtree.vc/jobs'>airtree.vs</a>

### US focused
- <a href='https://github.com/pittcsc/Summer2023-Internships'>Pittcsc</a> provides small, curated lists of open internship positions
- <a href='https://simplify.jobs/'>Simplify</a> is an excellent way to streamline the job application process. It autofills many applications for you

## Linux
While you don't need to use a Linux desktop, having a basic understanding of some of the fundamental unix tools such as `cat`, `grep` and pipes 
is invaluable. Many tasks you will need to do can be solved with unix tools. If you wanted to copy files from a remote location periodically 
such as a NAS you could write a python script or use software that provides this functionality or you can use `cron` with `rsync`. The advantage of
using these tools is that many of the edge cases have been dealt with or are well documented

The best way to get started would be to install a linux distro as a daily driver
### Guides
- <a href = 'https://linuxjourney.com'>Linux journey</a> provides a well thought out, easy to understand guide to most linux tools you'll need
