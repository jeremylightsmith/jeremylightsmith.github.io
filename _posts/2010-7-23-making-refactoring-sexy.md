---
layout: post
title:  "Making Refactoring Sexy..."
date:   2010-7-23 12:00:00 -0700
categories: refactoring
---
I've been gone from the M$ stack for quite a while - 2006 was the last time I was in .Net land. But recently, I've come back to it through one of my clients, and I have to say, I've been pleasantly surprised.

Between lambda expressions, closures, and extension methods, C# is looking a whole lot like Ruby these days. And with Resharper, working with Visual Studio feels a whole lot like using IntelliJ.

But that's where things get weird.

The client will buy Resharper licenses for any developers that want them, but I'm having a heck of a time showing people why Resharper is cool...

h2. Why Resharper is Cool

"Resharper":http://www.jetbrains.com/resharper/ is plugin for Visual Studio that adds refactoring support (among other things). The guys that wrote it also wrote "IntelliJ":http://www.jetbrains.com/idea/ the Java IDE that changed the "way the Java world writes code":http://martinfowler.com/articles/refactoringRubicon.html and raised the bar for Java IDEs..

I learned how to refactor by pairing with people like "Dan North":http://blog.dannorth.net/, "Matt Foemmel":http://blog.foemmel.com/, and "Charles Lowell":http://www.cogentdude.com/ and a bunch of other amazing ThoughtWorkers. We used IntelliJ. Every other week when they released a new version, we'd all pull it and as we wrote code, we'd find faster ways to do things and share them. Our language even evolved. We started talking to each other about inlining that variable, extracting that method, introducing a a field for that, etc. We started thinking and talking at the level not of individual code changes, but at the level where you're stacking 5 or 6 refactorings on top of each other.

And that's really what Refactoring is - a domain specific language for writing code.

Using this DSL, in a tool like Resharper, my personal coding speed is easily 2 times if not 3 or 4 times what it would be in the same language without it. And over and above that, even without it (say in Ruby) I still think in terms of chunks of work, refactorings.

h2. So what's the problem?

Despite the awesomeness of Resharper, despite pairing with me as I use refactorings to blaze through things that would have taken mounds of time otherwise, developers here fail to be impressed.

I'm not sure why.

Perhaps, the problem is that I haven't tried teaching them the language, the Refactoring DSL. Every language has a barrier to entry that is greater than zero. And Refactoring is no exception.

Perhaps a series of brown bags on Refactoring / Resharper is the answer.

Perhaps I should think about how I might be able to use "Where are your keys":http://whereareyourkeys.org/ to teach them the DSL.

If you've found a way to teach people the love of refactoring, I'd love to hear it...
