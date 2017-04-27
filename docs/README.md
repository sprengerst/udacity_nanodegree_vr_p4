# Puzzler

This project is done as part of the Udacity VR Developer Nanodegree program. The goal of this project was to teach me fundamentals in design and user centered thinking. This Github page shows the main project work routine, from start till the end. Also I have listed all user tests I did.

## Statment of Purpose

Puzzler is a mobile VR puzzle game for new VR users. It challenges them to 
solve a familiar type of simon-says puzzle in a new way.

## Final Result (Video)

In this video you can see how the app finally looks like.

<iframe width="560" height="315" src="https://www.youtube.com/embed/HMSIOC5l99M" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

# The Process

Now I cover the complete process of designing this application. This will cover Persona, Sketch and User Testing:

## Persona

### Lisa, 26 - Medicine Student
![Image of Lisa](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/lisa.jpg)

#### Cite:
"Man can alter his life by altering his thinking"

#### About:
Lisa is in the middle of her masters degree in Medicine. 
One of her research topics is in dementia so she 
is always searching for new ways to help struggling persons.
Also she loves it to solve problems and to challenge herself with
mind games. 

She doesn't have any experience in Virtual Reality, 
but is interested in new technologies.

## Sketch

This sketch is the one and only drawing I made to describe the game mechanics and environment in general it should be almost self explaining:

![Image of Sketch](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/sketch.png)

# User testing outcomes and iteration

Here are the testing outcomes from the different user tests. They all divide in Questions, Iterations #x and findings.

## Scale and Mood User Test

### Main Questions:

	1.) What do you think about the scale of yourself, is everything as big or small as it should?
	2.) Is the mood well established? What do you think, where you are?
	3.) Is the experience comfortable? Do you experience any strange or confusing stuff?

### Iteration #1:

	Leandra, 16:
	1.) I seem to be a little bit smaller than I normally am.
	2.) It seems a bit yellowish, like inside a cave with torches.
	3.) Some objects are flickering.

	Tatjana, 50:
	1.) The room seems to be bigger than normal. 
	2.) It looks like some kind of cell, it makes me feel a little bit claustrophobic.
	3.) Some objects are flickering, and the horizont behind the gate is very confusing. Is the room floating?

Here you can see the current state for the user testing:
![Before Iteration](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/1_2_screen.jpg)

### Findings:
	Good:
		- The ambient is great and is mysthic as it should be.
	
	Bad:
		- I think that a problem is in the camera position I highered the camera to make the protagonist feel taller.
		- Some objects are growing inside each other, I fixed that so flickering should stop
		- The skybox is confusing so added a new one with a horizont sun.

After applying my findings the scenary changed significantly:
![After Findings](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/after_design_iteration_1_1.jpg)

### Iteration #2:

	Leandra, 16:
	1.) Now the size seems to be good.
	3.) The flickering is gone.

	Tatjana, 50:
	1.) The room shrank
	3.) Now I know that the room is standing on the ground.
	 
## User Test UI Panels:

### Main Questions:
	1.) Appearance of panel
	2.) Clear meaning

![Panel Tests ](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/panel_design_real.jpg)

### Iteration #1:

	Leandra, 16:
	1.) Good contrast, good to read
	3.) Know what it should do.

	Tatjana, 50:
	1.) Nice color, nice highlight
	3.) Clear.
	 
### Findings:
	Good:
		- Everything seems to be clear
	
## User Test on Movement:

### Main Questions:
	1.) Speed of movement?
	2.) Feel uncomfortable?

### Iteration #1:

	Marina, 26:
	1.) Speed is a little bit too fast, I'm feeling deezy.
	2.) Camera position to near at the magic balls.
	
	
### Findings:
	Bad:
		- The speed of 2 was far too high so I set it to 5.
		- The camera was to near at the orbs so I placed the play waypoint away a little bit more.
		
### Iteration #2:

	Marina, 26:
	1.) Now it seems to be slower, but good.
	2.) Seems to be good now.
	
	
## Sound user test and other stuff (Final)
### Main Questions:
	1.) Does the sound feel comfortable?
	2.) Other stuff?
	
### Iteration #1:

	Marina, 26:
	1.) Failure sound is far too loud.
		
### What I did:
	1.) Sound volume of failure sound to 0.5 instead of 1.0.
	
### Findings:

	Bad:
		- I set the sound volume of failure sound to 0.5 instead of 1.0, because it was set far too high.
	
# Breakdown of final piece

Here I want to give you an brief overview on which are the main elements of the game all of them are controllable and include important mechanics:

## Welcome UI (Start Game)
This is the screen the user can see on start of the application, after pressing start he flies into the dungeon:
![Image of Welcome UI](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/final1.jpg)

## Orbs (Play Game)
Here you can see the main game mechanics in form of orbs. The orbs light up in random combinations:
![Image of Lightning orb](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/final2.jpg)

 You have to repeat the order they did that by pointing and clicking on them:
![Image of Selected Orb](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/final4.jpg)

## End UI (Restart Game)
This is the screen the users sees after succesfully finishing the puzzle:
![Image of Finish UI](https://raw.githubusercontent.com/sprengerst/udacity_nanodegree_vr_p4/master/docs/final9.jpg)

# Conclusion
It was a great experience to create this project I would recommend doing a Nanodegree to everyone, the amount of what you learn is amazing. This project was hard sometimes, but it was very nice to get an insight how user centered design is working and how user testing is done.

# Next steps:

It would be great to add more features to this application some of them could be:

	1.) Improved lightning 
	2.) High Quality environment
	3.) Multiple iterations and levels

# Link to additional work
Have a look at my other projects: 
https://github.com/sprengerst/


