---
layout: post
title: "Stupid or Solid"
date: 2021-02-17
---

    Hi, I'm Isabel and I write stupid code...  

    I wish I were kidding, but I do.  I am working towards writing solid code, but it
    is a challenge.  Some of the STUPID concepts are good for beginners and some are
    better after learning the basics, the same goes with SOLID concepts.  The concepts
    are as follows:
        **S**ingleton
        **T**ight Coupling
        **U**ntestability
        **P**remature Optimization
        **I**ndescriptive Naming
        **D**uplication
    and
        **S**ingle Responsiblity Principle
        **O**pen/Closed Principle
        **L**iskov Substitution Principle
        **I**nterface Segregation Principle
        **D**ependency Inversion Principle

    The S in stupid (singleton), I don't feel like is an inherently bad thing.  It
    is a well known pattern for a reason, but it should be understood that there may
    be better ways to design your program.  However, starting out singleton is kind
    of the easiest way to get the basic concepts down and start learning.  There's
    no reason to overwhelm a beginner.  

    Tight coupling is a concept that I feel like could be taught to beginners easily,
    but it often isn't.  The idea is that modules shouldn't strongly depend on each
    other.  So if one class uses another class and that class changes, there shouldn't
    be any reason to have to change something in the original class.  This is all
    design based, which really isn't a focus in many beginning programming courses
    unfortunately.  

    Untestability or, better testability, is a pretty simple concept to understand
    and we didn't focus on it until software engineering.  In data structures,
    testing was required and I think some other students were required to create testing
    for their programs earlier, but it wasn't standard across the board.  

    Premature Optimization I don't think I have a problem with, because most of the
    time I don't optimize.  This isn't actually a good thing in itself either, but...
    we can argue that it's something.  

    As for indescriptive naming, I feel like I've only gotten worse with this from being
    lazy... I like the last few sentences of this explanation though, "Computers
    just understand 0 and 1.  Programming languages are for humans."  

    Duplication is simple; work smarter, not harder.

    STUPID habits are easy to fall into, but they're luckily easy to understand and
    recognize.  SOLID is better programming, but I also feel like it is made up of
    concepts that are a little more difficult to understand.

    Moving onto the S in SOLID, single responsibility principle, is something I am
    not great at... I tend to get stuck in the singleton format. You would think it
    would actually be easier to have single responsibility classes, but I think I
    tend to focus on the final goal more than the steps or parts that build up to
    that goal.  This is where I struggle with the single responsibility principle.

    Open/closed principle is an idea I like a lot, but not really something I'm great
    at.  I think this comes back to the I focus more on end goal and big picture
    and push the smaller details to the side.  I think part of this is just focusing
    on getting assignments done versus actually working on a project.  I'm hoping I'll
    be able to focus more on planning and design in the future, but I'm not feeling
    great about it either.  

    Liskov substitution principle explanation confuses me.  Something, something all
    squares are rectangles, but not all rectangles are squares.... Something, something
    if it looks like a duck, swims like a duck, and quacks like a duck, then it is a
    duck... unless it has batteries?  

    From what I understand though is that interface segregation principle (ISP) helps
    with the Liskov substitution principle.  There's been a lot of talk about the
    importance of low coupling and high cohesion, and I do understand these properties.  
    Saying that, I'm still not great at implementing this principle anyway.  I do see
    how useful this idea is.  

    Dependency inversion principle (DIP) says that "abstractions should not depend upon
    details" and "details should depend on abstractions".  This is honestly another
    confusing one to me.  It almost just seems like it's saying to utilize interfaces.  
    This makes sense, but just the wording doesn't make sense to me.  

    In conclusion, I need to work on making my code less stupid.  
