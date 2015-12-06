---
layout: post
title: The Final Week
---

This week comes the close of the class itself. The last day of class was Wednesday and I took the last test on Friday. This was a really solid class.

Some thoughts on the last test... 

Scrolling over the questions on Canvas, my first thought was that forty percent (two out of five) of the questions and twenty-five percent of the points of the test seemed to be directly tied to understanding the `static` keyword of C++, which we spent a single lecture and a single in-class quiz going over. While the two questions seemed pretty simple to me (although often when that happens, it's because I've oversimplified it and I'm doing something wrong), the fact that they were focused on something that we didn't spend much time on seemed odd to me. The questions were also too similar... Anyone who was completely stumped by one question was probably clueless to the other one, which seems like doubly penalizing people.

My second thought was: for a test consisting entirely of writing code, putting it on Canvas is REALLY nice. Writing code without typing just feels wrong to me. If I realize toward the end of the exam that my logic is missing something in some spot on an early question, being able to go back and insert some code in places without the frantically-erasing-while-trying-not-to-smudge-everything-or-tear-the-page stage is really nice. And then of course the added ease of grading and ease of communicating the grading to the test-takers are both obvious wins.

The final two classes consisted mostly of going over the various styles of handle classes that can be built in C++. I'd learned most of this in OS earlier this semester (we'd had to implement something similar to Handle2), but it was a really good explanation and comparison of the different options a programmer could utilize (i.e. Handle2 to simplify the code, Handle3 to be more efficient with memory, etc.).

Not having any extra quizzes to offset absences for things like interviews was a bit disappointing, and I think unfairly penalized some people.

For any prospective students looking to enroll, this class is excellent as long as you don't already have a strong understanding of C++. If you already do, you might not get as much out of this class, because it's mostly a class about learning C++ to do fundamental OOP things, and not so much a class about OO design. That being said, Professor Downing is one of the best lecturers I've encountered at UT. He explains things well, involves you in the lectures, and answers questions clearly. I can't imagine anyone regretting taking this class.

Some additional thoughts: you also get exposure to some developer tools. Version control: Git, which you'll probably see in a lot of classes, is easy to pick up, often used in industry, and extremely useful. Unit testing/code coverage: gtest/gcov, which is very similar to other unit testing tools like JUnit that we used in Data Structures, is absolutely invaluable for writing code that works. Documentation: doxygen, which I'd never encountered before, is actually extremely useful and easy to use; it makes it pretty satisfying to write thorough documentation by outputting it in nice html. Memory checking: valgrind will teach you to avoid typing `new` and always type `delete` (or `delete []`) where `new` is needed, a great lesson in the perils of memory leakage. Finally, continuous integration: Travis-CI... undoubtedly this is a useful tool in industry and even in other classes, but in this class, with projects of such tiny scope, using this thing seemed a bit pointless.

#### Tip of the Week

For those interested in reading things about OO design, here's a [centralized source of OO design pattern information](http://www.oodesign.com/), including a forum where you can discuss what patterns would best fit your application.
