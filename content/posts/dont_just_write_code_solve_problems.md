---
title: "Don't just write code, solve problems"
date: 2021-01-21T14:38:25-03:00
author: "Douglas"
tags: ["software engineering", "career"]
featuredImage: "https://images.unsplash.com/photo-1562975327-29a8cbfd5be6?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1652&q=80"
subtitle: "Focus on problem-solving to improve your code skills"
draft: false
---

You’ve gotten stuck so many times while coding. We all have. Some hard, nasty problem. Many conditions. Maybe this can be broken down into smaller problems. Maybe some dynamic programming could help. There must be some famous algorithm behind this.

<!--more-->

“I know I wouldn’t have a hard time writing this code. If only I had any idea of what code to write.”

After being through this a few times, you start to notice patterns. Little strategies. There’s always some similar problem. A sketch always helps. All of these small things that don’t seem important but end up helping a lot.

Well, it turns out someone discovered and shared most of those “little strategies” a long time ago. In 1954, to be more precise. The man was named George Polya, and he was an amazing mathematician. He devoted a considerable part of his career to figuring out systematic methods of problem-solving, discovery, and invention.

![](https://cdn-images-1.medium.com/max/2000/1*535GVq8cPLmDew9-EH-TeQ.jpeg)

*Source: [Alchetron](https://alchetron.com/George-P%C3%B3lya#george-plya-3444d963-5689-46f2-8523-cd6b0fdef4f-resize-750.jpeg)*

I’m not sure if Polya expected 21st-century software developers to read his work, but it has certainly helped me. And I’m sure it will keep being valuable for decades to come.

Here’s what he has to say.

## Problem-Solving Is Not a Gift
> “Solving problems is a practical skill like, let us say, swimming. We acquire any practical skill by imitation and practice. Trying to swim, you imitate what other people do with their hands and feet to keep their heads above water and, finally, you learn to swim by practicing swimming. Trying to solve problems, you have to observe and imitate what other people do when solving problems and, finally, you learn to do problems by doing them.” — George Polya, How to Solve It

Polya states this quite early in his book, and with good reason. You can't start learning this if you think it is only for some gifted, special people.

## Problem-Solving Is Not a Purely “Intellectual Affair”
> “Teaching to solve problems is an education of the will. Solving problems which are not too easy for him, the student learns to persevere through unsuccess, to appreciate small advances, to wait for the essential idea, to concentrate with all his might when it appears.” — George Polya, How to Solve It

Determination and emotions play an important role when solving tough problems, as every software developer eventually will.

According to Mr. Polya, a good problem-solver is determined, as sometimes this person will have no idea of how to even start solving the problem. It is also important to have small victories — that is, to be able to solve smaller or related problems as well as different parts of the same problem.

## The Procedure

Whenever you’re going through the problem-solving process, keep these four steps in mind:

* Understanding the problem.

* Devising a plan.

* Carrying out the plan.

* Looking back and reviewing.

## 1. Understanding the Problem
>  “It is foolish to answer a question that you do not understand. It is sad to work for an end you do not desire.” — George Polya, How to Solve It

Before trying to jump straight to solutions, it is important to have all of the elements of the problem laid out. This will help you achieve a better understanding.

### Can you state your problem in one sentence?
> “Speaking and thinking are closely connected, the use of words assists the mind. Certain philosophers and philologists went a little further and asserted that the use of words is indispensable to the use of reason.” — George Polya, How to Solve It

This small exercise is very helpful for two things: convincing yourself you understood your goal and not spending too much energy with that understanding while you are focused on trying to solve it.

Explaining the problem to someone else is also helpful. As written in *The Pragmatic Programmer*, “rubber duck” debugging is simply forcing yourself to have a clear enough understanding of the problem that you can teach it to someone else. This enables you to have an idea and move forward.

### Are there constraints to be satisfied?
> “Therefore, let us, first of all, understand the problem as a whole. Having understood the problem,we shall be in a better position to judge which particular points may be the most essential. Having examined one or two essential points, we shall be in a better position to judge which further details might deserve closer examination. Let us go into detail and decompose the problem gradually, but not further than we need to.” — George Polya, How to Solve It

What are the boundaries of your problem? Write them down somewhere.

It can be a comment above the first line of a function you’ve written. It can be a list of bullet points on top of your design doc. It’s important to have them under focus while trying to come up with a solution.

Offloading multiple constraints from your brain is also a way of removing some of the balls from the “mental juggling” we do while trying to come up with a good idea.

Also, be careful if there are too many constraints. According to Polya, if you consider too many details at once, you may lose yourself. They may distract you from giving sufficient attention to the main point or even from seeing the main point at all. “Think of the man who cannot see the forest for the trees.”

### Can you draw a figure? Introduce suitable notation
> “An important step in solving a problem is to choose the notation. It should be done carefully. The time we spend now on choosing the notation may be well repaid by the time we save later by avoiding hesitation and confusion.” — George Polya, How to Solve It

This one is always a winner for me, especially when it's hard to wrap my head around some code-related problem. We all know we have to do some serious “mental juggling" sometimes, and when this happens, having sketches always helps.

That is because your drawings will help you offload some of those thoughts onto paper (physical or not) and make more room in your head to focus on the tricky parts. From flowcharts to block diagrams, any sort of notation will definitely help you understand things better.

[Miro](https://miro.com) has been my choice when doing this collectively with other people or if this understanding needs to be shared later.

My trusty unruled notebook also never leaves my desk, as it’s great for quick, ugly sketches.

![Photo by [Kelly Sikkema](https://unsplash.com/@kellysikkema?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral).](https://cdn-images-1.medium.com/max/11136/0*gdByZuA4JzmXF5L6)*Photo by [Kelly Sikkema](https://unsplash.com/@kellysikkema?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral).*

## 2. Devising a Plan
> “We have a plan when we know, or know at least in outline, which calculations, computations, or constructions we have to perform in order to obtain the unknown. The way from understanding the problem to conceiving a plan may be long and tortuous. In fact, the main achievement in the solution of a problem is to conceive the idea of a plan.” — George Polya, How to Solve It

Although it is hard to even visualize which steps are required to solve your particular problem once you’ve understood it, Polya has come up with a few things that you can do to help get you started.

One thing I’ll add here is this: Don’t mind the code initially. Solve the problem on paper first. Writing the code always seems easier in our heads and gets much trickier once you are trying to run it. Don’t do both things at the same time. First, solve the problem. “Run” an example on your notebook or on pseudo-code. Then, implement it for the machine.

### **Do you know a related problem?**
> “Good ideas are based on past experience and formerly acquired knowledge. Mere remembering is not enough for a good idea, but we cannot have a good idea without recollecting some pertinent facts.” — George Polya, How to Solve It

What Polya is suggesting here is that you need to know at least what kind of problem or family of problems you are dealing with. For software people, that will usually mean answering these questions:

* Is this an architectural issue?

* Are there architectural patterns that are commonly used in this scenario?

* Is this problem more on the level of an algorithm?

* Are there battle-proven algorithms that solve this kind of problem?

You’ll know you’re there once you’re able to find a problem that’s related to yours and has been solved before. Then you must ask yourself, “Can I use it?” Many problems may have some point in common, but the ones that share the most essential requirements or premises will probably be the most helpful.

### Could you restate the problem?

Can you look at the problem from a different perspective? There are multiple ways of doing so. Can you drop a part of the condition or some of the requirements? Can you state this problem under a more specific scenario?

If you are writing tests, thinking of simple examples that are created just by specific conditions of the problem is great for gaining ground on your final, more general solution. This leads us to…

### If you cannot solve the proposed problem, try to solve some related problem first

Or a related and also simpler problem. Like writing good software, exercising good problem-solving can be thought of as an incremental process. Don’t try doing everything at once. Building up your final code or even system design diagrams and ideas is a process that will benefit a lot from doing the same thing for smaller problems.

Even if your final artifact, such as a Git commit or design doc, is not very obviously an evolution of the last one, the ideas that you used to create it certainly are.

## 3. Carrying Out the Plan
> “To devise a plan, to conceive the idea of the solution is not easy. It takes so much to succeed; formerly acquired knowledge, good mental habits, concentration upon the purpose, and one more thing: good luck. To carry out the plan is much easier; what is needed is mainly patience.” — George Polya, How to Solve It

The 21st-century-developer version of this is “Think first, code later.” Once you are done understanding the steps of your algorithm or system design, implementing it later will be so much easier.

Polya states that good problem-solvers are capable of checking each step of their solution once it’s done and questioning it from start to end. From a purely analytical, mathematical line of thought, one wrong step destroys everything. This may not seem so immediately dangerous in software, but it can be just as deadly, as the nastier bugs will manifest themselves in the worst moments — and possibly under very specific circumstances.

For us, this translates to having good test coverage. If you didn’t test it, you didn’t question it. That means you’ve presumptuously considered your solution perfect, which we know is never true. Having this “Will it break?” mindset of constantly trying to come up with all the various failure modes of your solution is always helpful and will be conveniently documented with tests if you care to write them.

To summarize, convince yourself of the correctness of your solution.** **Don’t make that convincing all too easy.

## 4. Looking Back
> “Even fairly good students, when they have obtained the solution of the problem and written down neatly the argument, shut their books and look for something else. Doing so, they miss an important and instructive phase of the work. By looking back at the completed solution, by reconsidering and reexamining the result and the path that led to it, they could consolidate their knowledge and develop their ability to solve problems.” — George Polya, How to Solve It

Not looking back and appreciating the trade-offs of your solution is something that happens a lot when things are done with too much haste.

If it’s an algorithm, can you tell its time and space complexity? Does the code read well?

If you are making decisions that will have a system-wide impact, please write down those trade-offs on a billboard if you have to. Spending one hour reexamining the outcome of your work will save you so much more later on. Take a break if you have to, come back to it later. Being deeply immersed in the problem you are solving will probably cause you to have tunnel vision and forget about relevant details.

Also, it is possible that your solution to that particular problem *could *be generalized to be used in multiple scenarios. Think about that. Combined with good taste and careful thinking, creating new abstractions is a way of solving that problem for other people who encounter it.

## Wrapping Up

Polya’s *How to Solve It* is a book I’ll keep close to my desk during my entire career. Software engineering is a truly thought-intensive, problem-solving field and Polya’s timeless advice may help you in a time of need.

The book contains not only the four-step framework for solving problems but many other pieces of precious advice that fit the creative professions of the 21st century very well.

---
*Cover photo by [Fletcher Pride](https://unsplash.com/@fletcher_pride?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral).*

