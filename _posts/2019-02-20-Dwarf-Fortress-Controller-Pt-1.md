---
layout: post
title: DIY Dwarf Fortress Controller Part 1 | Planning the Controller
---

I'm personally a big fan of Dwarf Fortress, however, the UI... Let's just say that at this time it leaves something to be desired. Worse yet, I like to play some games on my TV, and would love to do so with DF, but, the interface just does not work for that, and to top it off, I don't have akeyboard to do that with anyways.

That's when inspiration struck! The DF menu system consists of submenus of submenus, going down until you find what you need, but the choices for most of the menu are 100% consistent. This led me to the idea of a small controller, similar to those old 20-questions toys, with just the yes/no/don't know buttons on them and a small LCD display.

So what do we need for this controller? Well, the only buttons that you consistently need in DF are the space bar and escape buttons. At other times, you may need any key on the keyboard, however those all are menu based, while the previous two always perform the same function not related to a given menu. So there are two keys right there, for our purposes, we'll call them Pause and Back. Next, we need a way to navigate the menus, which we can do with a simple set of up and down buttons, and an enter button, to make our decision. Finally, some menus also have left right motion, and others have multiple sets of left, right, up and down buttons, so we just need to add up, down, and super keys to our controller.

At this point, we have a controller with just eight buttons, much better than what DF usually asks for, twenty or more at least. But now we have an issue. Which menu are we choosing to go down? Simply enough, we can just program the hierarchy of the game onto whatever microcontroller we have, and then use a small LCD dsiplay, we can show the name of each menu, navigate into it, and then choose an interior option. Alternatively, if you believe that the organization of the menus is terrible and must be reworked, you can do that yourself as well if you go a bit more in depth with the programming.

Next time, we'll be looking at the materials we plan to use, and follow that up with some code, before finally putting the project together. Until then, good luck, and have a fun time with whatever other project you may be working on.
