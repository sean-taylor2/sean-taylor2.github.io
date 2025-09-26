---
layout: essay
type: essay
title: "Coding Conventions and he Human Element"
# All dates must be YYYY-MM-DD format!
date: 2025-09-24
published: true
labels:
  - Software Engineering
  - ESLint
---

## "It works, so it's not an error."

Anyone who takes the time to learn something new will likely need outside help to get to an acceptable level. This help may take the form of a tutor or teacher. In this situation, the tutor may take it upon themselves to micromanage. More likely than not, this will breed irritation - despite the fact that this may be a necessary part of the learning process. Musicians may find this as an especially relatable phenomenon.

For someone who installed ESLint for the first time, this same irritation is bound to follow. Code that was once syntactically correct will suddenly flash red lines. Someone new to the extension will look for syntax errors like a missing semicolon or parenthesis, only to find that they simply didn’t add a space between their function arguments and the opening bracket. To someone who never even considered formatting their code in such a way, this will obviously be frustrating. “After all, the code works. Why is that an error?”

While these are understandable and relatable thoughts to have, they come from a perspective that is missing the point. I outlined this in another essay, but the readability of code is not something to be overlooked. It’s vital to any cooperative environment, or even a solo environment.

## Navigating a Messy Room

Think about it. Say that you have a messy room. You may know where that paperclip is in your messy room, and it IS there. You put it there, so you have a better chance of remembering its location than anyone else in the world. Put someone else in that room, and they don’t have the same familiarity that you do because they have different habits on paperclip placement. They need to take time - precious productivity time - spent searching for that paperclip. This isn’t even accounting for the likely scenario of you just forgetting where you put it and taking time to search for it yourself. 

While not a direct 1:1 situation, this is the reasoning behind conventions. Messing up something small like an indentation is no big deal by itself, but small inconsistencies can build and build until it’s a pain to look at, and only serves to waste more and more time. 

All because you couldn’t clean your room. 

So, we keep things organized and in a well-understood manner to avoid such unnecessary time loss. So, while conventions may seem unnecessary, they actually aren’t when you consider the observable reality of your classmate's messy code.

## That's not everything...

I've been using examples of minor "grammatical" errors to describe coding standards, but in reality there's a lot more that ESLint isn't designed to catch. For example, you don't need to create comments for your code to run. And yet, it remains a very important convention that every developer had really ought to follow. Creating well documented code is challenging. In fact, I think that most software developers are terrible at describing what their code actually does (especially to a non-computer savvy audience). I used to participate in game modding/romhacking communities, and I would commonly find forum posts asking how to even use the software that contributers had otherwise worked very hard on. They had essentially handed others tools that were completely alien.

Here's the obvious part I'm getting at. Programming is not just for the computer. The human element should always be considered. At the end of the day, humans are going to be using and changing your software. They are going to expect documentation. They are going to expect methods and and variables to be structured a certain way. They are going to expect concise code. None of these things are enforced by the compiler, and a lot of them aren't caught by any programs, because they are conventions made for the ease of the human mind. 

During all this, what you may not have noticed is that the structure provided by such conventions are simultaneously accentuating how languages even function, providing a better understanding of how things work. In that way I can see that they work in favor for someone trying to learn a new language. 

For something that is not normally policed by the computer, the importance of conventions can not be understated.

## Closing thoughts on ESLint

As a result, I think ESLint is pretty helpful great policing tool to keep conventions solid. My code is more readable and consistent even to myself. With that said, I’m still bothered that the error red line is the same as the red line that shows for syntactical errors. In my opinion, they should be different just so I can tell that the code works and that I can come back and fix things to convention when I'm finished. Although, maybe I'm still coming from that beginner mindset. That small irritation is worth the process of becoming better at my craft.



