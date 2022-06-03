# Intro to Python

## Learning Goals

- Understand how to learn a new programming language
- Learn the benefits and philosophy of Python as a language

## Introduction

Throughout your career as a developer, it's highly likely that you'll be
expected to learn multiple languages depending on the companies you work for and
the kind of projects you're working on. After gaining confidence with one
language, like JavaScript, it can feel overwhelming and even scary to start over
from scratch with a totally new language.

Thankfully, we can tell you from experience that learning a new programming
language isn't so bad! While you were learning JavaScript, you were also
learning some other (even more) important skills: how a computer program works;
how to **debug code**; how to **search for help** when you're stuck; how to
**think like a developer**; and **how you like to learn**.

With those tools at your disposal, learning your second language (and your
third, and fourth) will be easier than the first.

To help you on this journey of your second language, Python, this curriculum will
start by introducing new syntax and showing the similarities and differences
between Python and JavaScript (they have more in common than you may think). Once
you've learned the fundamentals, we'll explore what makes Python unique and start
building new applications.

As you're learning, it's ok (and completely normal) to make mistakes: every
developer that switches between languages forgets syntax (is it `.toUpperCase()`
or `.upper()`?) and needs to [look at the documentation][python docs upper]
regularly. The most important things are to **write code** to develop your
muscle memory, and trust that you'll get better with practice.

## What is Python and Where Did it Come From?

Python is an interpreted, object-oriented programming language. Its high-level
built-in data structures and dynamic typing make it very useful for fast
development of new applications, as well as scripting or "glue" code to combine
existing components written in different languages. Python's simple, easy to
learn syntax emphasizes readability and therefore reduces the cost and
complication of long-term program maintenance. Python supports modules and
packages for containing code, which encourages program modularity and code
reuse. The Python interpreter and the extensive standard library are available
in source or binary form without charge on all major platforms and may be
freely distributed.

Guido van Rossum began development of Python in 1989 as a side project while
working at Centrum Wiskunde & Informatica (CWI) in the Netherlands. Van Rossum
thought of Python as a successor to the ABC programming language, one he had
helped create earlier in his career. He liked many of the features in ABC, but
took issue with many others. Now that he had the skill and opportunity to
create his own language, he took his favorite pieces from ABC and added or
changed functionality where he saw fit. He gave the new language the name
"Python" (after Monty Python's Flying Circus) and named himself "Benevolent
Dictator for Life." Despite the authoritarian title, van Rossum has always been
a champion of workplace inclusivity, especially with respect to gender
equality.

The interpreter and standard library were made available to
the public in 1991.

## Why Do Developers Love It?

Every programming language was originally designed to solve some kind of
problem. For example, JavaScript was created by Brendan Eich help developers
make web pages interactive.

Matz designed Ruby in order to **make programmers happy**. He developed a
programming language that would be simple to use, elegant to write, but capable
of building vastly complex things. A few of his own thoughts on Ruby sum it up
best:

> The goal of Ruby is to make programmers happy. I started out to make a
> programming language that would make me happy, and as a side effect it’s made
> many, many programmers happy.
>
> I hope to see Ruby help every programmer in the world to be productive, and to
> enjoy programming, and to be happy. That is the primary purpose of Ruby
> language.
>
> — Yukihiro Matsumoto

## What Can Ruby Do?

In the first two phases of the program, you used JavaScript primarily for one
thing: to build **client-side** web applications that run in the browser. While
it's true that you can use JavaScript to create other kinds of programs as well
thanks to Node, we've stayed true to the original intent of the language by
using it for frontend development.

Building web applications in JavaScript means we have all kinds of great tools
at our disposal thanks to working in the browser environment:

- Make network requests
- Update the DOM
- Listen for events
- Debug our code in the browser's developer tools

But it also means working in a **sandboxed environment** that can't take full
advantage of everything our computers are capable of, like accessing the file
system, or connecting directly to a database, or listening for HTTP requests.

Ruby, on the other hand, **can't** run in the browser. Learning Ruby means you
can build different kinds of programs: **server-side** applications. Writing
these kind of applications will mean familiarizing yourself with a new
environment. It also means you'll have a new set of tools and features at your
disposal, which is awesome! We can use Ruby to do all sorts of things, like

- Read and write files
- Listen for network requests and send responses
- Connect to a database to access and update data

Thanks to Ruby's flexibility, it means we can make all kinds of different
applications, not just web applications:

- Command line interfaces
- Web servers
- Games
- Web scrapers

Since you'll be learning a new environment, it's important to familiarize
yourself not only with Ruby's syntax, but also how to run and debug Ruby code.
Make sure to code along with the lessons to come so that you can gain confidence
in how to not only write code, but also to check what your code is doing and
explore all the great features Ruby has to offer.

Be sure to check out the resources below as well, and bookmark them for future
reference!

## Resources

- [About Ruby](https://www.ruby-lang.org/en/about/)
- [Ruby documentation][ruby docs]
- [Ruby Style Guide](https://rubystyle.guide/)
- [Ruby VSCode Extension](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
- [Ruby Solargraph VSCode Extension](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph)

[ruby docs]: https://ruby-doc.org
[python docs upper]: https://docs.python.org/3/library/stdtypes.html#str.upper
