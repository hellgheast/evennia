title: Where do I begin?
copyrights: Images: [©Griatch](https://deviantart.com/griatch-art)

--- 

> _This is a repost of an article I originally wrote for the Imaginary Realities e-zine, Volume 7, issue 3 back in 2015. It's not Evennia-specific but meant for a wider audience interested in making a text-based multiplayer game (MUD/MU*). Since IR is no longer active, I repost it here with only some minor cleanup._


When a new user has everything installed and drops into Evennia’s IRC support chat or mailing list, there is one question that we regularly get in various variations:

![painted image of the beginning of a road in autumn](images/yellow_world_by_griatch_art-d7a6e5n.jpg) 

  
_“Where do I begin?”_  
How to actually start down that long road towards your own game is an important question. Unfortunately it has no one-size-fits-all answer. So it usually leads to a series of counter-questions. In this article I will try to (without being Evennia-specific) pose those questions in a way that would not fit in a chat window. 

   
  

## What is your motivation for doing this?

  
So you want to make a game. First you need to make a few things clear to yourself.  
  
Making a multiplayer online game is a big undertaking. You will (if you are like most of us) be doing it as a hobby, without getting paid. And you’ll be doing it for a long time.  
  
So the very first thing you should ask yourself (and your team, if you have any) is why am I doing this? Do some soul-searching here. Here are some possible answers: 


- I want to earn recognition and fame from my online community and/or among my friends.
- I want to build the game so I can play and enjoy it myself.
- I want to build the same game I already play but without the bad people.
- I want to create a game so that I can control it and be the head honcho.
- A friend or online acquaintance talked me into working on it.
- I work on this because I’m paid to (wow!)
- I only build this for my own benefit or to see if I can pull it off.
- I want to create something to give back to the community I love.
- I want to use this project as a stepping-stone towards other projects (like a career in game design or programming).
- I am interested in coding or server and network architectures, making a MUD just seems to be a good way to teach myself. 
- I want to build a commercial game and earn money.
- I want to fulfill a life-long dream of game making.  
  
  
There are many other possibilities. How “solid” your answer is for a long-term development project is up to you. The important point is that you ask yourself the question.  
  
  
Answering this question you may find that you should not start a new project - maybe it’s better to build on or help improve something that already exists. Maybe you find you are more of a game engine developer than a game designer. Some answers may also suggest that you are driven by emotions of revenge or disconcert - emotions that may have abated later when the project most needs your enthusiasm and motivation.  
  
  
If your aim is to earn money your design goals may well be very different from those of a person who only builds for their own benefit.  
  
  
Whichever your motivation, you should at least have it clear in your own mind. It’s worth to make sure your eventual team is on the same page too.  
  

## What are your skills?

Once you have your motivations straight you need to take stock of your own skills and the skills available in your team, if you have one.  
  
Your game will have two principal components and you will need skills to cater for both:  
 

-   The game engine (“the code base”)
-   The assets created for using the game engine (“the game world”)  
    

  

## The game engine

The game engine is maintained and modified by programmers (coders). It represents the infrastructure that runs the game - the network code, the protocol support, the handling of commands, scripting and data storage.  
  
  
Creating your game engine from scratch can be a worthwhile and rewarding endeavour. It is however not a small one and if your main goal is to create a running game I would recommend building on an existing engine. It’s worth to take your time and do your research here. Searching the net and various MUD sites will bring you a slew of options. I will give some things to look for here.  
  
Whereas some engines/code bases offer a lot of pre-existing coded systems, there is no denying that your team will always need someone who either already knows some basic programming or is willing to learn it.  
  
When judging which engine you want to use, consider:  
  

- The engine’s community - hang out in the community/forums/chat surrounding the respective engine. Expect to need to ask a lot of “stupid” questions as you start developing (hint: no question is stupid). Is this a community in which you would feel comfortable doing so?
- Active development - is the code base actively maintained? If there are bugs in the engine, does it seem likely they will be fixed upstream or will you be patching bugs yourself? Or alternatively, are there many active users that can help you out with known quirks?
- Other available documentation - does the engine come with a manual? Are there online tutorials or other help resources to read?
- Which language is the engine coded in? What is it scripted in? Do you or your team already know this language or are you willing to learn it? 
- If you don’t know the language, do a few beginner tutorial so that you can at least vaguely recognize the syntax. Does the engine’s code seem easy to read and well documented? If the engine is poorly documented, the time of development may rise dramatically. 
- Something to remember here is that computers of today are very powerful. And while scaling may be interesting if your game really takes off, a text game is, for the most part, not very demanding. So I’d recommend you pick your language and engine not primarily based on performance but on what you feel comfortable and productive working with. 
- What is the engine’s license? This is mainly important if you plan to ever earn money with your game. Some common engines explicitly forbid commercial use.  
  

  

## Asset creation

Compared to the level of work needed to produce professional graphics for an MMORPG, detailed text assets for a mud are cheap to create. This is one of the many reasons muds are so well suited for a small team.  
  
  
This is not to say that making “professional” text content is easy though. Knowing how to write imaginative and grammatically correct prose is only the minimal starting requirement. A good asset-creator (traditionally called a “builder”) must also be able to utilize the tools of the game engine to its fullest in order to script events, make quests, triggers and interactive, interesting environments.  
  
  
Some game engines will offer generic online building tools while others will depend on the coders to create tools specific for their game. What you go for may be influenced by just how technically savvy your builders are and what skills they are willing to pick up along the way.  
  
  
Your team’s in-house builders will be the first ones to actually “use” your game framework and build tools. They will stumble on all the bugs. This means that you need people who are just not “artsy” or “good with words”. Assuming coders and builders are not the same people, builders need to be able to collaborate well and give clear and concise feedback.  

  

## So, where _do_ I begin?

  
  
Right, after all this soul-searching and skill-inventory-checking, let’s go back to the original question. And maybe you’ll find that you have a better feeling for the answer yourself already:

  
  

- If you are learning a new programming language, you should follow basic tutorials so that you can read, understand and replicate example code without being completely in the dark.
- If you have decided on your game engine you should dive into its manual and basic tutorials. Also make sure to introduce yourself to its community so you can get as much help as possible. 
- If the game engine offers tutorials on making some small example game, do that carefully. Even if the resulting demo game has nothing to do with what you aim to build. If there are no tutorials maybe you can instead find a full example code that you can examine in the same way. Not only will this give you a better understanding of how parts of the engine hangs together, it will also give you ideas for what you can do with it. If something is surprisingly easy to do, you might even be able to expand your plans! 
- If your game engine comes with pre-made game tools or building commands, the builders can start getting familiar with it. But keep in mind that these will not reflect the full capabilities of the game - your game is not yet built! So don’t set builders off to build large zone projects at this point. If they are building anything at all, it should be small test areas in order to agree on a homogenous form, mood and literary style.  
    

  
  
With a few tutorials and game examples under your belt you are ready to start some preliminary coding-tests of your own. You won’t be making a full game yet! Working without a step-by-step tutorial will give you an idea of just how easy or hard this stuff is to figure out in practice at your current skill level, chosen game engine and language. Make ample use of any manuals, help channels or other resources you can find - anything you will also have access to when you code the real thing. This allows you to judge the quality and usefulness of those resources at the same time. 

  
  
You or any builders may also get some building exercise here, using the commands and objects you create for simple testing. Here is a list of things to try out (you should be able to do these in any game engine worth its salt):  

- Change some phrasing in the output of an already existing command.
- Make a new command and add it to the game engine. Make it just echo back whatever argument you give it. 
- Code an object that echoes “tick” to everyone at its location every 20 seconds.
- Make a new command that creates new ticking objects where you are, but with a name given by you. 
- Make a room whose description changes every time you enter it.
- Make an object that deletes itself when its “health” property is changed to zero. 
- Make an “attack” command that randomly reduces the “health” property of a target object until it deletes itself.
- These are all simple things but it should give you an idea of what your chosen game engine is capable of and, most importantly, where to find help when you get stuck. If you can’t get past this step even with help you might need to go back and read up on the programming bit some more. Or maybe you should consider an easier game engine.  
    
    

## What is your scope?

  
We are now past the “things to do first”. Welcome to the things you do later.  
  
  
To reiterate, at this point you should have pondered why you are doing this and made an inventory of your available skills. You have gotten a first taste of the kind of coding work you will need to do and what that entails. You have built a few things to see how that works. Maybe you even changed game engine somewhere in the middle. Still ready to roll? Excellent.  
  
  
You should now hopefully have enough information to be able to realistically set the scope of your game.  
  
  
Everyone wants to make the best game ever. You want a whole world simulated in minute detail with next-generation artificial intelligence. You want instant action that puts Hollywood to shame and emergent storytelling worthy of Shakespeare.  
  
  
It’s okay to dream big, but your first goal now is to get something out. Something that players can actually connect to and give feedback on. Having players enjoying an early version of your game is a great motivational boost in itself, you should try to reach that stage quickly. You are aiming for a first version, not the ultimate version. All online mmo:s keep improving the game after release, that’s the name of the game. 

  
  
So keep your grand plans in mind but limit your scope for your first release. For a group of hobbyist developers (which is, frankly what almost all MU* development teams are) your motivational time is precious. You are likely not getting paid during development which means that it’s imperative that you set out to create something you are capable of finishing while still having fun. Adjust the scope to fit this time. If you run out of steam before this time you’ll know you went for too big a scope.  
  
  

## How to continue from here?

  
How to progress is depending on your preference. Some prefer to just jump straight into coding and figure out things as they go. It's not a bad idea to to sit down and plan a little first though - and remember that you want _a first version_ of your game at this point, not the _final, ultimate_ version. 

This is beyond the first question asked in this article (which is long enough as it is) but I have written about this process in [Evennia’s game planning documentation](https://evennia.com/docs/latest/Game-Planning). This reiterates some aspects of this article while expanding on others. 

  
… But in the end, remember that what kills a hobby game project will usually be _your own lack of motivation_. So do whatever you can to keep that motivation burning strong! Even if it means deviating from what you read in articles like this one. Just get that game out there, whichever way works best for you.