# Time Report and notes

# 2025-03-25 -- Start time: 20:25
Now playing: Janis Joplin's Greatest Hits, 1973 press.
<br> - Plan </br>

<br> To write the first lines of code -- I'll end when I feel like it. </br>

- Current progress

Made an input box using HTML for user to enter their username. Next to it is a box that submits the username and saves it to a variable. I also made it so that you can confirm the input using the enter key. Reason behind that being that I instinctively went for enter several times while testing the code, rather than clicking the button itself.

When you continue the username is printed using the following format "Player name: "username"".

Made a button that lets you "sell a rock for $1". This button adds 1 to a variable that is set to 0 as a default. When you press it the first time it prints "Total wealth: 1" and the more you press, the higher that number becomes.

- Problems during this session

Using document.write to print ended up breaking the program a lot. I asked my dear friend ChatGPT what to do to fix this, and was told to use something called innerHTML. The problem is that this stupid AI bot isn't able to give simple instructions so it just kept spitting out code I couldn't understand. Thus I had to figure out how it worked by mysef. Well, to be fair, I'm still not sure how it works, but it works, and that's fine enough for the moment. From my understanding document.write is purely JavaScript, but the innerHTML mixes them in a way where HTML takes care of the visuals and Javascript works as the brains. Using document.write the program just sort of ignores what came prior to that document.write function, leading it to kill itself, due to JavaScript not really being optimal for the visual aspects of a web page.

In any case, that works now and I'm fine with that. Other than that I had no major road blocks.


- Errors that came up this session to fix during the next

Nothing major, but the sell button shows up too early. I want to make it so that it doesn't show up until you have submitted your username. I'd also like to make it so that you can't continute without entering a username.

Other than that the goal is to just keep moving based on the plan.

Now playing: Pugh och Rainrock, Ola Magnell, Lucas Persson: Ett steg till, double-LP, 1975 press.</br>

# 2025-03-25 -- End time 22:30 -- Total time spent: 2h 5 minutes
