---
layout: post
title: "This Bugs Me"
date: 2021-02-04
---

**TOS Exercises 6.4, 6.5, 6.6, 6.7**

6.4 Exercise: Find the Oldest Bug  

    The oldest bug in Habitica isn't strictly a bug, but an accessibility issue.  The oldest open issue is that the app is [not compatable with voice over](https://github.com/HabitRPG/habitica-android/issues/180).  This issue has been open since December 10, 2015, which is almost since the beginning of the android and ios versions of Habitica.  There are comments within the issue post ranging from questions about specific requirements to contributors volunteering to work on the issue.  It appears as though there have been at least five merges related to making the app compatible with voice over and at least two other issues opened that were related to the same issue.  Despite the issue being open still, it appears as though it has been mostly resolved, but still has room for improvement.  When we commented on helping make the app more friendly to those who are color blind, we were denied this issue due to the staff not having enough man power to help advise with issues that are this large.  This would make me think that fixing this compatibility falls into the same category.  

6.5 Exercise: Create Your Bug Tracker Account  

    Habitica uses the GitHub issue tracker.  I have an account for GitHub, so no problems there!  

6.6 Exercise: Reproduce a Bug  

    A current bug that we plan to work on and have gotten approval to work on is that when a user tries to message an account that has been deleted, there's no sort of error message.  The issue is posted [here](https://github.com/HabitRPG/habitica-android/issues/1401).  This is actually a fairly easy error to reproduce, because all you need is an account to send the message and a deleted account.  Everyone on our team has an account, mine having the handle lallyir.  An account with the handle DoomedTester2021 was created, added to our party, everyone messages, then deleted.  After this account was deleted, I tried to message it again.  What happened was that I was able to type a message and it looked as though I would be able to send the message, however, after pressing send the message flashes like it is sending and then the message reappears in the text box.  Nothing informs me that the user no longer exists and the reason I can't send a message.  This was a simple bug to reproduce since you don't have to do anything too strange.  Some of the other bugs include attempting to do something quickly and after some other specific event has happened.  For instance, you can have pets that get promoted to mounts and if you quickly equip your pet immediately after they have been promoted, you are still able to equip it as though it's a pet.  Therefore, to recreate this error, you have to get your pet to a level that they will be promoted to a mount and work quickly from there.  This is also not ideal because once you do that with one pet, you can't recreate the bug again with the same pet, but have to reproduce the bug with another pet which includes hatching and feeding another pet.

    Fork Bomb has since been assigned to this issue and we have been given the message format that a user should receive:  
![](https://raw.githubusercontent.com/CSCI-462-01-2021/Fork-Bomb/main/assets/images/Pop-up-format.PNG)  

6.7 Exercise: Bug Triage  

    This exercise is a little more difficult to do with the way bug reporting is set up for Habitica.  Bugs can be added directly to the GitHub issues page, but they can also be emailed and then are triaged by staff and added to the GitHub after that.  Normal contributors don't have access to the reports that have been emailed and therefore not yet triaged.  However, even though most of the issues on GitHub have been added by the staff and developers, several of the newer issues may be the same issue just in different parts of the app.  A main problem currently is that information and statuses are not updated automatically and there have been several posts stating that as follows:  
    [Tavern Page Blank](https://github.com/HabitRPG/habitica-android/issues/1479)  
    [Coins and Items Don't Update When Selling Thins](https://github.com/HabitRPG/habitica-android/issues/1466)  
    [Phantom Pet Eggs](https://github.com/HabitRPG/habitica-android/issues/1460)  
    [Progress Not Always Shown in Quests](https://github.com/HabitRPG/habitica-android/issues/1436)  
    [Dailies Not Being Loaded When App Starts](https://github.com/HabitRPG/habitica-android/issues/1440)  
