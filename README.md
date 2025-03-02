# Rules For Young Programmers

Following Robert Schumann's [Rules For Young Musicians](https://jmm.people.si.umich.edu/blog/schumann%27s_rules_for_young_musicians.pdf) ([mirror](https://www.scribd.com/document/391732530/schumann-s-rules-for-young-musicians-pdf)) in merit and style, here's a set of maxims and aphorisms for aspiring and practicing programmers alike, in no particular order. As stated in the foreword to the original article:

> Once you have read them, you will find yourself reading them again and again, finding the wisdom they contain more absorbing and rewarding each time.

## Usage

As we believe the practice of programming is very similar to practicing piano or other classical instrument, there's too much nuance in the discipline for one to become a good programmer learning from written resources only.

Therefore, the presence of another person in your education process is of utmost importance. That person can be your mentor or a senior colleague.

These "Rules..." are meant to be discovered together, preferably with younger programmer asking a more seasoned one on the nature of a specific item in this list, so that they can engage in a meaningful discussion about it.

## I

The most important thing is to cultivate the sense of Seeing. Take pains early to embrace understanding while sight reading, as reading code makes the most of the programmer's work.

## II

Each code editor has syntax highlighting – use it to spot functions, control statements and loops before you see them.

## III

Develop a strict discipline of writing your code in a consistent manner. For a seasoned programmer, every indentation or empty line matters and makes sight reading easier.

## IV

Lehman's classification of [S-programs, P-programs and E-programs](https://users.ece.utexas.edu/~perry/education/SE-Intro/lehman.pdf) is a very useful concept. They are highly correlated with [Clear, Complicated and Complex](https://cynefin.io/wiki/Cynefin_Domains) domains in the Cynefin framework.

## V

Strive to write S-Programs well and beautifully; it is necessary for a practitioner to be able to write rock solid, fast and small programs, rather than a mediocre large system.

## VI

Algorithms are good examples of S-Programs. If you're looking for a next exercise, try to implement and then understand the inner workings of an algorithm in the language of your choosing.

## VII

In real life, scaffolding doesn't stay with the building when it's completed. Don't fool yourself, it's a wrong metaphor. A better one would be of a skeleton.

## VIII

A young programmer practices program designs that can be understood by other programmers; you'll keep the rest of your career practicing designs that can be understood by anyone.

## IX

If you believe there's only one way to accomplish a certain task, only one framework, only one language or only one programming paradigm, then it's the same as believing there's only one way to structure a sentence with given meaning in the English language.

## X

Avoid mixing up declarative and imperative code. It's like answering the question "Where are you going for holidays?" with "Well, for starters I'm going to check the oil level in my car engine".

## XI

Don't confuse divergent meanings of the `=` symbol across paradigms. A mathematician might say this determines equality between two sides. A functional programmer might say it's about binding a name to a value. An imperative programmer will say that's the assignment operator that mutates the program state.

## XII

Acquaint yourself early with the idea that any program you write will be studied by others and it's your responsibility to teach them to orient themselves in your code. Each program constitutes an act of teaching.

## XIII

Never write tests for how the code was written. Write tests for how it's going to be used.

## XIV

A good metaphor for the reactive programming paradigm is electricity. You are not interested in the principles that make the current flow inside the wire, you expect to just connect the wires to make things work.

## XV

Acquire early a skill to compare and concatenate paths by eye. Many programmers spend hours just to find out their program is not pointing to the right file, directory or a network address.

## XVI

Learn to seek for the precise terminology and use it deliberately. For example, a procedure and a function may seem similar, but there's a consequence in the meaning and application of each one.

## XVII

Develop understanding of [The principal programming paradigms](https://www.info.ucl.ac.be/~pvr/paradigmsDIAGRAMeng108.pdf) from the book "Concepts, Techniques, and Models of Computer Programming". This will make you appreciate the paradigm you are working with even more and draw deeper connections between the worlds of declarative and imperative programming.

## XVIII

The prevalence of classes in languages such as Java spoils the mind and depletes the diversity found in other languages and paradigms. Break out of that spiral by noticing that OOP is built on the foundation of only three elements: a procedure, a closure and a state cell, and thus, there is no mysticism in using classes.

## XIX

Learn to use divide and conquer strategies when debugging the code. If you know there's a bug somewhere between line A and B in your code, develop hypotheses which will introduce point C in between A and B, which can be then validated. That way you'll be able to discover whether the bug is in (A, C) or (C, B).

## XX

Develop understanding of multiple languages and paradigms in addition to knowing a few of them expertly.

## XXI

Many face dread when taking over someone's program. Do not let it overcome you. The moment you reach a conclusion that some code should not be changed no matter what, you become a slave to the mistakes of the past.

## XXII

It's a programmer's responsibility to introduce quality to the code. If you don't devote a bit of time for that, nobody does.

## XXIII

One might believe that constraints only impose restrictions on the thing being constrained. But an outdoor concrete bench, while still preventing you going straight through it, enables sitting as a new possible pattern of behaviour. Similarly, [constraints](https://cynefin.io/wiki/Constraints) shaping the reality of your program not necessarily just reduces the set of options at hand.

## XXIV

Learn to appreciate functions, especially the pure ones. They are often simpler to conceptualize, because they can be considered in separation to the rest of the program.

## XXV

Within the Cynefin framework, the act of writing a program lies in the [Complicated domain](https://cynefin.io/wiki/Cynefin_Domains), as the outcome (the program being complete or not) can be easily predicted with a high degree of accuracy by an expert. The consequence of the aforementioned is that the act of program writing can both be mastered by one and replicated by many.

## XXVI

A good metaphor of a function is a set of equations relating its input with the output. That way even the order of instructions can be dropped, and in some languages (like Lustre), that happens.

## XXVII

Code that has served its purpose needs to go. Make a decent funeral out of it, and do not invoke the dark arts of Necromancy because you are not ready to part with it yet.

## XXVIII

Most times, the program or module you are writing is a part of many in the living environment of a larger system. Even if you might spend lots of time on this one part only, be wary of getting too protective about the fruit of your work. Mind that in a living organism, only cancer cells wall off from the greater purpose of achieving the whole work.

## XXIX

Not every problem is solved by a program.

## XXX

Even if your technology seems to be neatly fitted in the confines of your IDE, don't shy away from learning how to use terminal and how to script around your tools.

## XXXI

Both backend programming and frontend programming require some level of aesthetics. Look at the beautiful examples and develop an urge to seek the ugly places in the codebase and improve them. Not always you'll have the time or power to do so, but that should not propel you into indifference.

## XXXII

Many great tools are combined together to achieve something new. A Docker container and a compiler, for example. A crucial cognitive skill is learning the basic tools up to such a level so that one can troubleshoot problems when the tools are combined together.

## XXXIII

Learn the boundaries of your basic tools. Oftentimes, a developer is introduced to both a language and a library or framework at the same time and they cannot separate one from the other. Similarly, a trog is a dog combined with the nearest tree. I wonder why people don't use this term more often?

## XXXIV

If you read Conway's Law carefully enough, it tells that sometimes it's insufficient to just shape the code at hand. Take a look around you and notice how people organize themselves around the tasks – maybe then you'll discover new ways to influence the system design.

## XXXV

There's a deep connection between programs and symmetries. Similarly as a square can be mirrored and rotated while preserving its shape, the money transactional logic can transfer money between accounts while preserving the total amount of money in the environment under which the system operates.

# Contributing

Contributions are always welcome.

In order to:

1. Add new rules: fork this repository and create a pull request with your additions.
2. Discuss existing rules and make corrections: create an [issue](https://github.com/makimo/rules-for-young-programmers/issues) in this repository.
