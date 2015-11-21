---
path: getting-started
layout: page
title: Getting Started as a Software Developer
---

A software developer starting their career will likely only have mastered a small set of the skills in this list. Recent graduates in computer science who started programming during college will likely only have mastered a few top level items from the following list (although some computer science graduates either started programming long before college or end up writing much more software during their undergraduate years). Graduates from coding schools have probably not yet mastered any of the skills on this list; if starting from scratch, 12 weeks of learning at saturation levels is barely enough time to learn how to operate the tools of software development well enough to bootstrap further self-directed learning.

Depending on variety of experiences and the quality and amount of useful coaching, mastering the skills on the getting start list probably takes between 2 and 4 years of full-time work as a software engineer.

#### Algorithm & OOP Concepts

* Understands four fundamental data structure (List, Array, Hash, Tree) and how abstract functional structures (Stack, Queue, Heap, Set, Map/Association) can be constructed from them.
  + Can identify and apply appropriate functional structures to problems they elegantly solve.
  + Can identify which fundamental data structures have native support by core languages.
  + Has in-depth knowledge of Arrays and Hashes, including abstract "big-O" notation and APIs in core languages.
* Can identify and apply organizational principals and idioms at the function/object/module level, even if language does not support explicit support.
  + Encapsulation
  + Information Hiding
  + Inheritance
  + Polymorphism
  + Open/closed principle
* Can identify and apply strategies for repeat execution of logical blocks
  + Iteration
  + Recursion
  + Memoization

#### Language Mastery

* Ability to use documentation for core languages, frameworks, packages to apply technologies and debug issues quickly. Can solve issues in core technologies that do not have relevant Google search results or Stack Overflow articles.
* Understands idioms and best practices for tools and technologies being used. Applies best practices when developing new software modules. Opportunistically brings existing, deficient modules up to best-practice state.
* Understands variable scoping for core languages.
  + Can identify source of all variables in a function/method definition (local, argument, closure, global).
  + Understands “platonic” variable lifetime (i.e. if garbage collection is perfect and instantaneous).
* Understands references vs. values (a.k.a. mutable vs. immutable; object vs. primitive) for core languages.
  + Can identify when mutating vs. replacing operations.
* Understands input, output, and input/output (mutated) function arguments. Understands languages' function return-value support.

#### Engineering Practice

* Ability to read source code and demonstrate understanding, both from internal and external sources, during the software development process.
* Makes software changes in “complete” manner. For example:
  + Verifies that software written works correctly and in expected manner.
  + “Garbage collects” when removing usage of variable/class/constant/etc.. Searches for all other uses of it, removes definition if last usage was removed.
  + When adding new variables/object/abstraction looks for additional opportunities to replace code with new constructs.
* Something about tests and testing.
* Proficient in use of git for version control.
  + Create a new feature branch and merge.
  + Squash commits on a feature branch.
  + Rebase a branch onto another branch-point.
  + Determine the difference between branches, both as commits and as code.

#### Teamwork

* Is a member of on-call rotation. Can diagnose production issues and fix or escalate as appropriate.
* Seeks to understand needs of internal and external customers and prioritizes bug fixes and feature development according to customer needs. Communicates need for “internal” (developer-facing) development/refactoring/technical debt work to manager/product team/internal customers when it is necessary.
* Identifies when feature requests or scope changes that will have schedule impact are raised, calls out if not already acknowledged.
