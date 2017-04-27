# udacity_nanodegree_vr_p4

Introduction
Outcomes
Story of the process
User testing outcomes and iteration
Breakdown of final piece
Conclusion



Statment of Purpose
===================
Puzzler is a mobile VR puzzle game for new VR users. It challenges them to 
solve a familiar type of simon-says puzzle in a new way.

Persona
=======
![Image of Lisa](https://github.com/sprengerst/udacity_nanodegree_vr_p4/blob/master/lisa.jpg)

Lisa, 26 - Medicine Student

"Man can alter his life by altering his thinking"

Lisa is in the middle of her masters degree in Medicine. 
One of her research topics is in dementia so she 
is always searching for new ways to help struggling persons.
Also she loves it to solve problems and to challenge herself with
mind games. 

She doesn't have any experience in Virtual Reality, 
but is interested in new technologies.



name, age, occupation, quote, experience level and some sentences

The end users for Puzzler are likely to be people who are new to VR,
but who have already experienced various games in their life. They are 
probably going to be in their mid twenties and own a next-gen smartphone. 
And I hope they enjoy puzzle games!


Sketch
=======
![Image of Sketch](https://github.com/sprengerst/udacity_nanodegree_vr_p4/blob/master/sketch.png)


User Test Begin
===============

Main Questions:

	1.) What do you think about the scale of yourself, is everything as big or small as it should?
	2.) Is the mood well established? What do you think, where you are?
	3.) Is the experience comfortable? Do you experience any strange or confusing stuff?

Iteration #1:

	Leandra, 16:
	1.) I seem to be a little bit smaller than I normally am.
	2.) It seems a bit yellowish, like inside a cave with torches.
	3.) Some objects are flickering.

	Tatjana, 50:
	1.) The room seems to be bigger than normal. 
	2.) It looks like some kind of cell, it makes me feel a little bit claustrophobic.
	3.) Some objects are flickering, and the horizont behind the gate is very confusing. Is the room floating?
	 
Findings:
	Good:
		The ambient is great and is mysthic as it should be.
	
	Bad:
		- I think that a problem is in the camera position I highered the camera to make the protagonist feel taller.
		- Some objects are growing inside each other, I fixed that so flickering should stop
		- The skybox is confusing so added a new one with a horizont sun.
	
Iteration #2:

	Leandra, 16:
	1.) Now the size seems to be good.
	3.) The flickering is gone.

	Tatjana, 50:
	1.) The room shrank
	3.) Now I know that the room is standing on the ground.
	 

User Test Panel:
================
1.) Appearance of panel
2.) Clear meaning

Iteration #1:

	Leandra, 16:
	1.) Good contrast, good to read
	3.) Know what it should do.

	Tatjana, 50:
	1.) Nice color, nice highlight
	3.) Clear.
	 

User Test Movement:
===================
1.) Speed of movement?
2.) Feel uncomfortable?

Iteration #1:

	Marina, 26:
	1.) Speed is a little bit too fast, I'm feeling deezy.
	2.) Camera position to near at the magic balls.
	
What I did:
	1.) Speed to 5 in Gamelogic
	2.) Align waypoints correctly
	
Iteration #2:

	Marina, 26:
	1.) Now it seems to be slower, but good
	2.) Nothing
	

	
Final User Test
===============
1.) Sound?
2.) Light?
	
Iteration #1:

	Marina, 26:
	1.) Failure sound is too loud
	2.) Back floating is confusing
		
What I did:
	1.) Sound volume to 0.5 