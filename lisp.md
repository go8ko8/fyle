<a href="RECURSIVE FUNCTIONS OF SYMBOLIC EXPRESSIONS AND THEIR COMPUTATION BY MACHINE (Part I)">Recursive Functions of Symbolic Expressions and Their Computation by Machine</a>
- > A Class of Symbolic Expressions. We shall now define the S-expressions
(S stands for symbolic). They are formed by using the special characters: "(" ")"

- <i>The "mother of lisp" paper by John McCarthy</i>




<a href="http://xahlee.info/UnixResource_dir/writ/lisp_problems.html">Fundamental Problems of Lisp</a>
> - Syntax Irregularities
> - The other fundamental problem in the language is its cons cells as its list construction primitive. <br>
> - Why Lisp's Cons Problem Never Got Fixed?

<a href="https://vimeo.com/6624203">Organizing Functional Code for Parallel Execution; or, foldl and foldr Considered Slightly Harmful</a> - Guy L. Steele, Jr.; Sun Microsystems
- regarding the "<a href="https://news.ycombinator.com/item?id=814632">get rid of cons</a>"

<a href="https://lambdafaktorie.com/embedding-lisp-in-c-a-recipe/">Embedding Lisp in C++ – A Recipe</a>
> - No matter if you are programming in Python or C++, Lisp is invariably what holds up the scaffolding behind the scenes
> - This is true because Lisp is the Lingua Franca of your compiler.
> - Being a List Processor and working with Abstract Syntax Trees, your compiler may essentially be regarded as a Lisp engine.

### Books:

P. Seibel, Practical Common Lisp, Apress, 2005.
(Common) Lisp is my language of choice, for various reasons. It has some features that make it the most comfortable language (for me), like macros, closures, REPL… This book is the best introduction to Common Lisp and to programming in the Lisp Way. Read it and then move on to the books below.

Online version: http://www.gigamonkeys.com/book/

P. Graham, ANSI Common Lisp, Prentice Hall, 1996.
Another great introduction to the language, with lots of exercises (which seems to be a lost art in today's programming books). It is part tutorial, part reference, with extended examples and interesting appendices.

P. Graham, On LISP, Prentice Hall, 1993.
Advanced Lisp programming, mostly using macros. After experiencing the power of metaprogramming in Lisp, you won't be content with "conventional" languages anymore.

Online version: http://www.paulgraham.com/onlisptext.html

TexInfo version: http://mirror.lug.udel.edu/pub/fink/distfiles/onlisp.texi.gz

Nice PDF version: https://bitbucket.org/blevyq/onlisp

D. Hoyte, Let Over Lambda, Lulu.com, 2008
Advanced Lisp programming, mostly using closures. This powerful construction is now making its way into more mainstream languages as well.

E. Weitz, Common Lisp Recipes, Apress, 2016.
This is a reference book of advanced CL techniques, but I've read it cover to cover, and learned a lot from it, even though I've been using Lisp for more than a decade. It covers, in addition to the core language, some of the best open-source libraries, as well.

S. E. Keene, Object-Oriented Programming in Common Lisp - A Programmer's Guide to CLOS, Addison-Wesley, 1989.
Everything you wanted to know on how to use CLOS. I would recommend this even to people who doesn't use CL, just to show them that there are other ways to do OOP.

When you feel comfortable with CLOS, move on to:

G. Kiczales, J. des Rivières, D. G. Bobrow, The Art of the Metaobject Protocol, MIT Press, 1991.
This book explores object-oriented reflective techniques for language extension & design, through the derivation of Common Lisp's object system. It also lets us peek under the hood of CLOS, and serves also as a MOP reference. A bit dry, but interesting book.

P. Norvig, Paradigms of Artificial Intelligence - Case Studies in Common Lisp, Elsevier, 1991
A book on building AI systems - with Common Lisp at its best.

H. Abelson, G. J. Sussman, Structure and Interpretation of Computer Programs, 2nd Ed., MIT Press, 1996.
Also called the "Wizard Book" or "SICP", this is an introduction to programming in general using Scheme as a medium. An abundance of exercises helps you understand the concepts. There is even a videocourse downloadable on the internet.

Online version: http://mitpress.mit.edu/sicp/

TexInfo version: http://www.neilvandyke.org/sicp-texi/

Nice eBook version: https://sicpebook.wordpress.com/

R. K. Dybvig, The Scheme Programming Language, 4th Ed., MIT Press, 2009.
An introduction and reference to the Scheme language (R6RS).

Online version: http://www.scheme.com/tspl4/

Personally I like the 3rd Edition better, which covers the smaller R5RS language, and thus more compact - you'll learn the rest from your favorite implementation's manual anyway. Also the R5RS standard is a common ground every implementation can do.

Online version: https://www.scheme.com/tspl3/

C. Queinnec, Lisp in Small Pieces, Cambridge University Press, 2003.
The complete guide to write your own Scheme/Lisp compiler. This is also called the modern-day version of Allen's Anatomy of LISP (see below).

J. Allen, Anatomy of LISP, McGraw-Hill, 1978.
This book explains how to write an interpreter or compiler to (an old version of) lisp. Its non-lispy notation may be strange at first, but it serves an important purpose: abstract definitions and the actual representations are completely separated. After so many years, it's still a deep and very enjoyable read.

P. Henderson, Functional Programming - Application and Implementation, Prentice Hall, 1980.
This book is similar to Anatomy of LISP, but using a strictly functional language. It teaches the functional paradigm, and then moves on to show how to implement a compiler for the language (on a SECD virtual machine). Additional topics like lazy evaluation and non-deterministic computation are also included. Contains exercises (with solutions!).

D. P. Friedman, M. Felleisen, The Little Schemer, 4th Ed., MIT Press, 1995
A fun read in dialogue format leading you step-by-step to the Y-combinator and the construction of a Scheme interpreter.

D. P. Friedman, M. Felleisen, The Seasoned Schemer, MIT Press, 1995
This is the sequel to "The Little Schemer", using the same didactic style, introducing some more advanced language features, like destructive methods and continuations.

D. P. Friedman, W. E. Byrd, O. Kiselyov, The Reasoned Schemer, MIT Press, 2005
The third book in the series take us to the field of logics, building a Prolog-like language in the process.

D. P. Friedman, M. Wand, Essentials of Programming Languages, 3rd Ed., MIT Press, 2008
This is a book about interpreters, and the languages they interpret. Its main message is that any sufficiently complex system needs a DSL, and for that, an interpreter. It also discusses various types of languages while creating an interpreter for them, adding one feature at a time.

source: http://salvi.chaosnet.org/texts/programming.html

____
