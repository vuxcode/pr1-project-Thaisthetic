# Time Report and notes

# 2025-03-25 -- Start time: 20:25
Now playing: Janis Joplin's Greatest Hits, 1973 press.

- Plan 
 
To write the first lines of code -- I'll end when I feel like it.

- Current progress

Made an input box using HTML for user to enter their username. Next to it is a button that submits the username and saves it to a variable. I also made it so that you can confirm the input using the enter key. Reason behind that being that I instinctively went for enter, to submit, several times while testing the code, rather than clicking the button itself.

When you continue the username is printed using the following format "Player name: "username"".

Made a button that lets you "sell a rock for $1". This button adds 1 to a variable that is set to 0 as a default. When you press it the first time it prints "Total wealth: 1" and the more you press, the higher that number becomes.

- Problems during this session

Using document.write to print ended up breaking the program a lot. I asked my dear friend ChatGPT what to do to fix this, and was told to use something called innerHTML. The problem is that this stupid AI bot isn't able to give simple instructions so it just kept spitting out code I couldn't understand. Thus I had to figure out how it worked by mysef. Well, to be fair, I'm still not sure how it works, but it works, and that's fine enough for the moment. From my understanding document.write is purely JavaScript, but the innerHTML mixes them in a way where HTML takes care of the visuals and Javascript works as the brains. Using document.write the program just sort of ignores what came prior to that document.write function, leading it to kill itself, due to JavaScript not really being optimal for the visual aspects of a web page.

In any case, that works now and I'm fine with that. Other than that I had no major road blocks.


- Errors that came up this session to fix during the next

Nothing major, but the sell button shows up too early. I want to make it so that it doesn't show up until you have submitted your username. I'd also like to make it so that you can't continue without entering a username.

Other than that the goal is to just keep moving based on the plan.

Now playing: Pugh och Rainrock, Ola Magnell, Lucas Persson: Ett steg till, double-LP, 1975 press.</br>

2025-03-25 -- End time 22:30 -- Total time spent: 2h 5 minutes

# 2025-03-31 -- Start time: 18:45

Now playing: Björn Afzélius & Globetrotters: Nio liv, 1985 press. </br>

- Plan

Fix at least one of the problems that came up during last session. Begin working on the stage module. I want to make two buttons that show up when you have $10. When you choose either one they should trigger two separate bits of text to show up, dependant on which one you press. Each text box should have another button that puts you into the next stage.

- Current progress

I did fix the sell button showing up too early. And I have added the following:

++ Two buttons that lets you progress to stage 1 when you reach $10 wealth on stage 0 </br>
++ A transition screen between stage 0 and stage 1. It keeps a placeholder text and a confirm button to get you to the next level </br>
++ Upon clicking the confirm button you are sent to the next stage. There the value of a click goes from $1 to $10 </br>
++ Passive income of $2/second on stage 1 </br>

- Problems during this session.

The major one... this is the second time I write this time-report. I forgot to save it before and quit Chrome without saving. In the code I had some minor road blocks around the way. The one I got stuck on the longest was that between the transitions I kept having the wrong amount of money at the start of Stage 1, and even as soon as I started the game. I fixed this by updating the function that prints the wealth on screen to trigger more often. Other than that nothing huge.

- Errors that came up during this session to fix during the next.

Apart from the functionality I wanted from the last session that I didn't do anything about, there are no bugs as of now. Meaning that the next session I will just keep pushing through.

Now playing: Lena Nyman & Berndt Egerbladh: Ja Visst Gör Det Ont, 1976 press. </br>

2025-03-31 -- End time 23:25 -- Total time spent: 4h 39 min

# 2025-04-07 -- Start time: ~14:20

Short(er) library session

- Plan

Make a randomizer to create a way of creating a probability of making it to the next stage or not. Implement it into the program as much as possible, limited time today.

- Current progress

Randomizer created and added so that it's connected to the confirm button. I need to be at home with more time to make it work with the actual stage transition. I believe it might take a couple hours to figure out and implement properly. But, after that I think it's going to become easier to progress. At that point I just have to redo what I've already done 4 times to create each stage and transition.

- Errors that came up during this session to fix during the next.

  Nothing specific. Just realized that this functionality I'm looking for now is more "advanced" than I expected. Need more time and focus.

  2025-04-07 -- End Time 14:52 -- Total time spent: 32 minutes.

# 2025-04-16 -- Start time: 13:00

Now playing, Laufey: Typical of me, EP, 2024 press. </br>

- Plan

Implement the randomizer and see if I can get stage 2 going. If I can do that I think I should be able to create the rest of the stages fairly easily during my next session.

Overall time spent: 17h 14 min
