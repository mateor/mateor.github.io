---
layout: post
title:  "Math to support self-taught CS."
date:   2015-02-05 16:41:51
categories: math
---

##Foundational Math concepts

#### Get past the fact you may not have a Computer Science Degree.



This list is intended to show the base level math you would have encountered during an undergraduate CS degree. If you do not have a CS degree, this is the math they will teach you and this is the math a prospective job might expect you to understand. It is not exhaustive!
However, if you know this list, I believe you would be well prepared for any standard new grad CS job.

I spent most my the time cutting things off this list.
I promise, if you know how to program, you can do this.

###Things We Are Skipping
I am leaving off two big chunks that are useful, but unlikely to be used in your day-today life or in an interview.

1. Most of calculus, specifically the method of comparing function complexity through limits and derivatives. This is a useful skill but not so critical as to warrant the time it takes to learn it, especially if you have other holes. You can skip this for now.
2. Induction. If you are comfortable with recursion, you already have a good intuition about what induction is. This is a useful skill as well, but getting comfortable with it is a time investment somewhat equal to the rest of the whole list. Learning it as-needed is okay.


##__The Must-Have Math list__

These are the skills that are must-haves if you wish to approximate an undergraduate CS degree.
Outside of the probabilities section, they are all meant to be bite-sized. Don't budget anymore than 15-20 hours per section!
Even that is more than you need. Several of the below can be well-understood in an evening or two.

**1. Probabilities**
===============

#####__This is the big one__

* Terminology
    * Understand what median, mean and so on. Learn to recognize when problems are asking for one of them.
* Combinatorics (not the whole field! Concentrate on the specific in each section.)
    * combinations and permutations, with or w/o replacement.
    * This is the big thing on the list because these problems come up in regular programming all the dang time.
*  Look for questions and practice them. [Here is a good link ](http://www.mathsisfun.com/combinatorics/combinations-permutations.html) that gives an overview of the types of questions that
it would be good to recognize on sight.

**2. Logic**
================
* Terminology, again.

    * You should understand truth tables.
    * You must learn the basic rules of inference. This is some small memorization. But you should know what it means when someone says transitive or commutative. Someday they will, I promise.

* Understand Universal and Existential instantiation and propositional logic.

This entire section can be done in a weekend.

**3. Set Theory**
=================

Again, don’t fret. Just get comfortable with the terminology and you are almost there.

* Know what a union and an intersection are.
* Be able to apply the algebra of sets.
    * Don’t worry! If you learned the rules of inference, they are the same.
* This stuff really does come up but it is actually pretty simple. You don’t even have to memorize all the formulas just know the basic rules.

**4. How to reduce equations**
============================
* You perhaps already know how to do this. There are two rule sets you must know for CS math.
    * Exponent rules (how to multiply, add, divide things with exponents)
    * Log Rules (how to change bases etc. There are a handful, learn them.)

**5. Log rules**
==================
* Yeah, I put it twice :). Logs are a fundamental building block of CS.
If you kinda sorta know what a logarithm is, maybe could fudge your way to explaining bases...not good enough.
You can learn it all in one hour, it will pay off for your whole career.

**6. Number Theory**
========================
* This may not always come up but it certainly can and it is useful in lots of ways.
* Counting
    * Terminology again. You should know what prime, relatively prime are.
    * Learn what makes a number prime, work through Euclid’s GCD algorithm.
    * Basic rules of odd/even. When is a number odd, when is it even?

* Modulus
    * If you understand modulus and know what it means for two numbers to be congruent, I consider that a win.
    *RSA
* After you learn the two above bits, work through the RSA algorithm. You don't need to compute it or be able to derive inverses.
 If you can understand how RSA works, then you should be good on Number Theory.

**7. Summations**
========================
* This has scary looking syntax, but all it means is adding a sequence of numbers!
    * Recognize a geometric and arithmetic sequence when you see one.
    * Know how to convert that sequence into a concrete number for some n.

**8. Graphs and Trees**
===============================
* Congratulations, if you are this far into the list you are basically done.
Especially because you don’t have to learn any new math to work on graphs and trees. This is often the last section of CS math courses.
* You may already know this material and if not, well you have graduated from self-study math and begun self-study algorithms!


## Conclusion

This list is meant to be manageable. I did not want to tell you to go pick up a high school trig book and work your way
through the entire history of math. That is too much! You are probably already teaching yourself to program, you don’t need an additional career’s worth of work dumped in your lap.

The truth about math is this: **Math is fun and everything new you learn about it will help you to better understand complex things.**
But even if you don't think it is fun, you can still learn it without it consuming your life.

**Supporting material**
==================
If I was designing a self-study course around this list, I would plan 2-3 weekends for probability and one week for every other section.

The last bit of good news is that there is a college course that teaches you all of these subjects in one semester.
It is called Discrete Math and it is a survey course that touches on everything on the above list.
The even better news is that probably a third of the course is spent on induction, which I allowed you to skip!

There is a book by [Rosen about discrete math](http://www.amazon.com/Discrete-Mathematics-Applications-Kenneth-Rosen/dp/0072899050).
Do one section a week (skipping induction and anything else not on this list) and you will have conquered this list in 3-4 months.

You can do it. I know, because I did it myself. Good luck!
