[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Jayden Leader
### Student number: 47934980

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
My encounter design was specifically curated in order to encourage experimentation and easy fun with the games mechanics, particularly in regards to how to approach enemies, who are often positioned in such a way that they are able to threaten the player before the player can threaten them.

My broader level design includes small areas hidden away behind breakable objects, such as in (DocImages/Discovery.png)

Where a secret area has been presented that can be avoided entirely if the player wishes to advance, but they are rewarded both with a sense of discovery at uncovering the area, mastery at defeating the challenge within and relief upon using the health pickup at the end. The Players' sense of discovery is further heightened by discovering the teleporter, which allows them to skip the now largely redundant introduction to breakable walls and objects.

### 1.2. Drama
Encounters are designed in such a way that, once cleared the area becomes safe apart from environmental hazards, Areas such as the one shown in (DocImages/Drama.png) allow for players to defeat enemies there and then exist in a relatively safe space, which confers a sense of relief and reduces the tension of the moment.

On a far larger scale checkpoints are used as sections of the game are completed, reducing the tension as the risk of lost progress is lessened considerably, and providing relief from the potential tense moment of risking losing significant progress right before the checkpoint.

### 1.3. Challenge  
The level seeks to challenge players to master the games movement, primarily jumping. It encourages players to plan their jumps, even the simplest of jumps have very small margins of error. To do this players will need to employ physical and intellectual skill, tracking the movement of the floating platforms and timing their inputs appropriately to maximise their ability to progress.

I sought to increase difficulty throughout the level to match Players rising mastery of the games mechanics by combining several causes of difficulty in an area. in (DocImages/Challenge1.png) The simple jump over the acid and the jump onto the moving platform above the spikes are both introductory challenges presented at the beginning of the level which players should master relatively quickly.

Further on in the level however is (DocImages/Challenge2.png) Where a player must make the same jump across an acid pit, however a floating platform covered in spikes floats above menacingly, creating a small window of timing that a player must exploit to progress safely. Furthermore enemies have been added to the other side, capable of targeting the player from a distance, prompting the player to continue moving forward to address the threat.

### 1.4. Exploration

In (DocImages/Exploration.png) to progress past the combat introduction section the player can choose to progress the same way they have been going, or to explore, breaking the breakable wall and entering a secret area underneath the previous sections.

Furthermore I made the aesthetic choice to present safe areas using the green grassy tiles and dangerous areas (with enemies and environmental hazards present) as the yellowed dead grass tiles as a visual indicator of the area. I've also used the background tilemap to highlight the difference between the initial cave segment and the mountainside the player comes to later in the level, implying a change of scenery and pushing the player to uncover more of the backdrop hidden behind the mountains. 

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Passthrough Platforms Acid,Spikes , Moving Platforms
(DocImages/SB1.png) 

I chose to present these mechanics in a single combined area, introducing jumping, then jumping over hazards, then jumping onto moving platforms in sequence as concepts that build off the core jumping mechanic. Grouping together the "Environmental" pieces of the game would allow the players to intuit how they work, and to experiment freely in a smaller section of the area

### 2.2. Checkpoints, Weapon Pickup(Staff & Gun),Chompers, Spitters, 
(DocImages/SB2.png)

Introducing checkpoints before the rest of the "Combat" mechanics was vital, as they are introduced after the environmental introduction and present an immediate danger to the players progress. Encouraged by the safety net of the checkpoint, players can experiment with their weapons as they are introduced to the two enemy types and their behaviours, developing strategies for how to approach them in future with the tools they have and understanding how they threaten players.


### 2.3.  Keys, Health Pickups, Breakable Boxes
(DocImages/SB3.png)

Health Pickups are introduced after the potential danger of the Combat section, hidden behind breakable blocks which are clearly cracked. Players can intuit or reveal through trial and error that blocks can be broken. This introduction can be skipped if players discover the breakable block in the previous area and move past it into the secret area, as it introduces concepts that the player will have already discovered.

## 3. Spatiotemporal Design
### 3.1. Molecule Diagrams
(DocImages/MD1.png)
(DocImages/MD2.png)
(DocImages/MD3.png)

### 3.2. Level Map – Section 1
(DocImages/LM1.png)

### 3.3.	Level Map – Section 2
(DocImages/LM2.png)

### 3.4.	Level Map – Section 3
(DocImages/LM3.png)

## 4. Iterative Design (~400 words)
(DocImages/Iterative.png)

Throughout my level several features have needed to be altered as I go, I've made several updates to my design, both before and after finalising as factors influenced the final design. 

Chief among them the positioning of my platforms and their end points, due to the moving nature of the platforms and the difference in their movement duration depending on speed and distance traveled, getting platforms to synchronise to allow players to advance required several itterations, ensuring that it worked no matter how much time passed.

Furthermore the placement of enemies had to be considered constantly, as platforms and environmental hazards were added, being knocked back by enemies was a risk I had to choose to either embrace or mitigate and throughout playtesting several updates were made, particularly in the later sections of the level to increase difficulty in certain areas and reduce the challenge in others.

I feel as though several features could be further improved through iteration, particularly the placement of environmental hazards such as the floating platforms with spikes, as their positions could be further altered to change how they apply pressure to the player as they traverse the environment


	