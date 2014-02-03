---
layout: post
title: "A symbol as a chest of drawers"
date: 2014-02-02 20:37:25 -0800
comments: true
categories: [Emacs, Lisp]
---

I'm reading [An Introduction to Programming in Emacs Lisp](https://www.gnu.org/software/emacs/manual/eintr.html). I like this passage:

> A symbol can have both a function definition and a value attached to it at the
> same time. Or it can have just one or the other. The two are separate. This is
> somewhat similar to the way the name Cambridge can refer to the city in
> Massachusetts and have some information attached to the name as well, such as
> "great programming center".
>
> Another way to think about this is to imagine a symbol as being a chest of
> drawers. The function definition is put in one drawer, the value in another, and
> so on. What is put in the drawer holding the value can be changed without
> affecting the contents of the drawer holding the function definition, and
> vice-versa.

English works this way. The symbol `drive` has (several) function/verb and
value/noun definitions, as do many other English symbols. This overloading of
symbols is common in human languages but is uncommon in computer programming
languages. Emacs Lisp is a so-called "Lisp-2" because it can associate a symbol
with two or more different kinds of things at the same time, as opposed to a
"Lisp-1" like Scheme.
