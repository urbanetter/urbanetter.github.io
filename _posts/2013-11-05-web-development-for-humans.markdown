---
layout: post
title:  "Web Development for Humans"
date:   2013-11-05 20:17:00
categories: development
---

This post was a long time coming. It is about *development culture*. The development culture I wish I have at work. (I mostly have it at the moment, by the way, which makes me quite happy :) ) Since there is the word "culture" in it, this means that there is no proper "right" or "wrong". The following is based on my observations in my last few years of web development and loosely based on various blog posts, the most recent one being from ircmaxell, titled ["Beyond Inheritance"][beyond_inheritance].

First and foremost is the fact, that we should code *for humans first*. Because the computer is pretty good at complaining when it can't understand something. But unfortunately, there is no parser error when a human doesn't understand your code. The WTF per line of code do not matter for the compiler, after all, the code works (tm).

But as we all know, there are big differences in the way we code. There are probably as many ways to write a piece of software as there are programmers multiplied by the number of programming languages (and probably some more). But which way is the desired one, which one should you aim at?

I would say the answer to this question is: *none*. Because there is not a single way which is superior to code. There is only a path to improve. If you read your own code from a year ago you should see what you would do differently. You should see  how you improved. This does not mean you're a bad coder. In fact, if you wouldn't see anything you could improve it would mean that you didn't learn a lot in the last year.

But being on a path also means to be constantly evaluating the direction you're heading. And I found that there are a lot of people who are screaming "THIS WAY, THIS WAY", some subtle roadsigns and some stones to trip over. The good thing is, that basically moving on the path is the thing which makes you a good programmer. You stop being a good coder when you stop moving, *regardless of the position you're at*.

Now having a plan where you're heading is always a good thing. And coming back to the blog post title I think you should aim to *write your code for humans*.

The practical impacts of this decision are to put the *readability and therefore the maintainability first*. If you start to go in this direction you often find that your code is too complicated. You start to realize that 15 classes for just fetching some answers from a HTTP-API is too much. You start to realize that it is not always good to abstract something if you do not need the abstraction. If the reader or user of your code does not have to get all your smart abstractions to find out what the code does, why not save the hassels for her?

For me, I realized that often, more "straight forward" code is better readable. It may not be as beautiful and as easely extendable as other code, but it sure is better maintainable. And the longer I work in this business the more I tend to put more weight on the maintainability side. As stated above: This does not mean you should not use abstractions. They help a lot. &lt;bold statement&gt;But if you think about that poor guy which has to maintain your code, maybe you do one abstraction less and one thing more explicit. You will write more maintainable code. And therefore better code. &lt;/bold statement&gt;.





[beyond_inheritance]: http://blog.ircmaxell.com/2013/11/beyond-inheritance.html