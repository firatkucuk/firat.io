---
layout: post
title: How I create a software from scratch
date: 2021-04-27 11:12 +0200
tags: [development, tips]
---

Building high-quality software is a tough task and also a never-ending story. After a while, the software gets bigger and becomes hard to maintain. So a clean architecture might be helpful to maintain our software. But no matter what, eventually, our code will need refactoring or rearchitecting. So our code should also support proper change management. Here are the steps that I use or try to use when I develop software from scratch or just implement a story.

# 1. Take some time to think about it

Immediately opening our IDE and start coding might not be the best approach. Let's think about the problem, maybe discussing a little bit with colleagues. Or just sketching on paper but we should spend some time on it. And the initial design won't be perfect so try not to be a perfectionist and stick on a simple and primitive solution.

# 2. Implement using testing

Tests are our best friends and not a waste of time. We can gain confidence about refactoring our code and be sure about the scenarios. If you don't have tests you can never know a small change in the code will break other functionality.

## Some tips about implementation

- Use strong types if possible
- Use languages like kotlin which forbids nullability or use strict checks about nullable types
- Use better naming conventions
- Use Value Objects and Enums, especially in hasmaps
- Use design patterns

# 3. Iterate multiple times

The initial design might not be perfect and we might find out some other design aspects while we are developing so it might be good to iterate multiple times of the development phase.

# 4. Use linting and code metrics

Code style check and code quality metrics are crucial parts of development. We need to measure line of code of a method/class or complexity of method. Checking cyclic dependencies and measuring coupling. After checking all those items we can finalize our code.