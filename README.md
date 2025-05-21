# Project Notes

Included in time-report.md.

# Project Summary

This unnamed piece of junk program is a short story-driven incremental game that you probably shouldn't play. The story, which is about person trying to make a lot of money -- is about as bad as the code, and there's no joy to have with either part. I am not usually this pessimistic, but this thing has been constantly putting me at my wits' end since I started it. So, I have about 2% love and 98% hate for it. 

I started out fairly optimistic, and thought it would be quite an easy project. While it's not even especially technically advanced in its current state, it took me a lot of effort to get there. At first I began working mainly with functions. At the start, my idea was to make the whole program mainly using functions. At first it worked really well, I used ChatGPT sort of as an assistant for some part, but at this stage I was actually working mostly through my own mind. The main things I ended up asking AI for help with was the following:

- How to make submit your name work by pressing enter, apart from only using the button
- How to print text without using document.write(), since it kept breaking the program. This was replaced with using innerHTML to print on screen.
- How to create a passive income function that adds balance to the player's currency every second.
- How to create a randomizer -- that I later scrapped for the sake of my own sanity.

What ended up happening however, was that I kept coding myself into corners. I made functions that carried variables, which lead to me not really being able to keep track of what was going on. Later I also had problems with transitioning from stage to stage. At some point I had two or three different functions doing the same thing, without being able to reuse anything -- the program broke, and it was so messy I didn't know where to start to fix it. At that point I decided to start over. But, since I had learned so much from round 1, restarting wasn't as daunting as it might sound.

Starting over, I actually pasted all my code into ChatGPT, told it what my intended functionality was and asked something along the lines of "What a are some steps I could take to make this program more modular and reusable?". It gave me a few really good ideas that are fully implemented, and some of it is actually the base for the program in its current state. For example: 

- To make each UI-screen more reusable, they are all written in their own blocks of HTML, and later printed using the same method as the old version. The output is decided by variables.
- Instead of storing stage related javascript and HTML variables as global variables or inside functions, these are now in an array.
- Instead of making a transition function for every stage, like before, there is now one main function that handles it all through the array. Since there is a legal, and an illegal route option, there are also two handling that choice right before the progress function.

I just want to be clear with the fact that, even though I used ChatGPT for parts of the project -- I did use it in a way that was more of a shortcut for Googling, rather than as a way to just cheat my way through the project. It probably saved me time in the way where I didn't have to sink a bunch of time into half-relevant Stack Overflow discussions and barely get the answer I needed. But, I still poured a good amount of hours into it, landing at a total of around 27 active hours. Which puts me below the 30 hours that I was aiming for. But to also make sure I didn't ruin the program that now works fairly well, I didn't want to jeopardize anything by trying to re-implement the randomizer, add more gameplay etc. I've also sort of lost interest in this project, and would rather possibly do something else.

As for things to be improved, there are a few things. Design is something I was wanting to do, but didn't really get into at all. Of course, the randomizer to add some probability into whether or not you'd be sent to the next stage. The story elements right now are pretty boring. At the same time I don't have the ambition to improve it as it stands. Other than that, it's pretty much what I meant to create, and it works as intended. Albeit the numbers are tweaked to be quick to present, so it's very unbalanced and quite short, even for a smaller incremental game.



# User Guide

The program is quite simple and easy to wrap your head around. Here are some steps:

- Enter your name and click submit, or press enter. -- Choose wisely, because you can't change it afterwards, unless you reload the page.
- Once greeted with the worst UI you'll ever lay your eyes upon, feel free to read the story text, or start selling your rocks by pressing the sell button.
- To progress you have to press that button several times.
- When you've pressed it enough times, you'll get an option to progress to the next stage.
- Choose yes, and you get to choose between the legal or illegal route -- whatever you choose makes no difference, it's only story dependant, and even then it's minor.
- Choose no, and you stay at the current stage. But don't worry, you get the option to proceed to the next stage through a button.
- After choosing a route you just do the same thing again, but now your sell value will have increased and there's also a passive income now.
- Once you have done this for a while -- in this version until you reach $10,000, you'll get a pop-up saying you've won the game. Press "Ok", and the page reloads and you can indulge in this wonderful experience once again!
