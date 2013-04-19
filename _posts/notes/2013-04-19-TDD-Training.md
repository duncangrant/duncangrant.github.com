---
layout: post
category: notes
tags: [TDD]
title: TDD training notes
---

Two day training by Jason Gorman - Codemanship

1. Covered TDD of classical OO
2. Covered TDD of London school OO

Basic rules

1. Write a failing test
2. Write the simplest code to pass the test
3. Refactor to remove duplication
4. Write the assertion first
5. See the test fail
6. Write meaningful tests
7. Triangulate
8. Keep tests and model code separate
9. Isolate your tests
10. Organise your tests to reflect model code
11. Maintain your tests
12. Tests should test one thing
13. Don't refactor a failing test

Recommended approach to implementation is to do an 2-3 hours per week until habit begins to stick.  I don't really have time for this.  Could probably do occasional 30 minutes to encourage habit but not enough.  Might consider alternative approach where each week I pick one to focus on and try to get that one habit "fixed".  In theory I'd be proficient in 3 months.  Probably working from top to bottom wouldn't be best approach.

Stuff I still haven't gotten clear about TDD - as it was outside scope of course.

1. TDD for dynamic languages.  Supposedly unit tests "that you would need anyway" are the best way to ensure interface between classes is maintained.  Yet JG's approach didn't deem to enforce this.  Possibly the missing step here is the large "acceptance" test recommended in GOOS.

2. TDD at the edges.  It seems like most of my work (time not code) is on the edges.  If you don't TDD interactions with 3rd party code then how do you ensure that the expected behaviour of that code doesn't change?

3. TDD only seems to work well in popular modern types languages,  Works OKish in python and doesn't work in things like SQL.  Possibly.


