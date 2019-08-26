---
layout: post
title: "HW2: Responses"
date: 2019-08-26
---

  Today, I'm comparing common concerns from the articles "No Silver Bullet" 
  by Frederick P. Brooks, Jr. (April 1987), "Kode Vicious: Cherry-Picking and the 
  Scientific Method" by George V. Neville-Neil (August 2013), and "Why Google Stores 
  Billions of Lines of Code in a Single Repository" by Rachel Potvin and 
  Josh LevenBerg (July 2016).  
  
    One major concern between all articles is code complexity.  Increased code
    complexity leads to difficult team communication, going over cost, and 
    overall delays.  Team communication can often be over understanding of 
    other's code particularly due to different styles and how well documented 
    it is.  From using peer programming in labs and at hackathons, I've noticed
    how differently people will implement code that functions in the same way and
    it makes you problem solve differently, which is a actually a really good thing!
    From lack of understanding, more complex code is harder to work with, 
    including using it with other applications or changing and adding to 
    the code.
  
    Another major concern is what "No Silver Bullet" calls conformity.  They 
    mean conformity to different interfaces, but also with different people.  In 
    "Kode Vicious", the same idea is talked about when it refers to merging 
    branches and Rachel Potvin and Josh LevenBerg address as well.  George V. 
    Neville-Neil specifically refers to when to merge code.  He starts with 
    the answer of periodically, but that is vague.  The end conclusion, which 
    is not absolute and maybe different from what works for others is you merge 
    when you have a working and tested branch.  Google is able to manage merge 
    conflicts through staying in a single repo which has software to test and 
    either reject the changes or undo them if tests fail.
  
    Both of these problems really pertain to two things, testing and communication 
    within your team.  "Kode Vicious" talks about using the scientific method 
    during software development.  Everything should be written down and created 
    tests should be the same as hypotheses to prove or disprove, which you keep all 
    of to learn and be reminded of what you've done already even if it has been 
    disproven.  By starting with tests, you can continue to revise code and check 
    if the new portions are working, while making sure you don't break the rest 
    of your code at the same time.  
    
    As for communication in teams, that can be difficult.  People in the teams need 
    to be willing to compromise in addition to understanding each other and one 
    another's code.  My Software Engineering team seems like we'll be able to 
    compromise, but also actually make decisions.  I also think that having someone
    to make sure that everything is tested as it should be, though people will 
    write there own tests, and someone to manage merging of the code and handling 
    merge problems.
  
  
Articles:

  Brooks, "No Silver Bullet Essence and Accidents of Software Engineering," in 
      Computer, vol. 20, no. 4, pp. 10-19, April 1987. doi: 10.1109/MC.1987.1663532

  Neville-Neil, "Kode Vicious Cherry Picking and the Scientific Method," in 
      Communications of the ACM, vol. 56, no. 8, pp. 32-33, August 2013.
      doi: 10.1145/2492007.2492019

  Potvin and LevenBerg, "Why Google Stores Billions of Lines of Code in a Single 
      Repository," in Communications of the ACM, vol. 59, no. 7, pp. 78-87, 
      July 2016. DOI: https://doi.org/10.1145/2854146
 
