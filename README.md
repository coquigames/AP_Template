# ThirdPerson Action Platformer Template
### Unreal Engine 4.12+

[Forum Post](https://forums.unrealengine.com/community/community-content-tools-and-tutorials/97643-free-thirdperson-action-platformer)

## Release 1.1

[Latest Trailer](https://www.youtube.com/watch?v=6rWOd2f7eHs)

**NEW FEATURES:**

**Air Jump and Dash** - New abilities! You can now air jump (double jump / triple jump) with customizable number of times and impulse. You can also manually slide with customizable speed and duration!

**Grapple System** - Shoot grapple and swing freely, or pull yourself to object (think Attack on Titan or Bionic Commando for those old timers like myself lol)

**Power Ups** - You can now easily add permanent or temporary abilities to your character. Includes UMG widgets for both cases.

**Dynamic Camera** - Took some tips from a GDC presentation on the camera system in Journey. The camera now adjusts FOV and boom arm length based on pitch. Also there is an offset while the character is standing still (rule of thirds). While sprinting the camera pulls back (seen in many games).

**Multiple character Select** - Added 3 characters (children of master character BP) to demonstrate how easy it is to change abilities. You can switch characters at any time with a key and each character has certain stats / abilities (one is strong but slow, another is weak but fast). I included a UMG widget with the character name and portrait. As well as an easy alert system. Due to the nature of the Character C++ class, I am restricting the switch only when the characters are idle.

**True Portal System** - Similar to the game Portal, now you have a portal that shows the content of the destination. Easily create as many portals as you want. Teleports player only from one side.

**Ladder System** - You can now go up and down ladders. Ladder has customizable stats (height, width, number of steps). Ladders can be single or double sided.

**Endless Runner Mode** - New mode added where the character is running endlessly. There are "boosts" that speed up or slow down the character. The purpose is to have a section in the game where you can force a chase scene or obstacle course.

**Other Updates:**
-Added switch that opens door example
-Added corners to the edge example
-Added example of tube edge climbing (more flexible in shape)
-General improvements on the climbing code
-Bug fixes

**Controls:**

**Spacebar** - Jump / swim straight up
**Left Shift** - Sprint
**Left Alt** - Crouch / swim straight down
**C** - Change camera mode
**E** - Interact / climb / grab / press switch / climb ladder
**R** - Toggle between Aim Mode - allows you to shoot your grapple
**Left CTRL** - Toggle walk mode
**1,2,3 Keys** - Change between characters


## Release 1.0

[Initial Trailer](https://www.youtube.com/watch?v=KSRnJrdP_qc)

**FEATURES:**

** 1 .Basic movement and camera controls**

Sprint
Crouch
Crawl
True first peson camera


**2. Basic Platforming setup**

Falling platforms
Dissapearing platforms
Spline-based platforms
Timeline-based platforms


**3. Hero Abilities**

-Wall climbing
-Rope climbing
-Edge climbing
-Sliding
-Zipline


**4. Basic Swimming Setup**

-Customizable breath timer
-Two swimming modes
-Air bubbles and more

**5. Basic Traps**

-2 Basic trap types
-Customize the speed, direction, and instant death conditions
-Ragdoll death sequence


**6. Basic Puzzle setup**

-Each switch supports up to 5 actors
-Have as many switches as you want
-Customizable playrate, movement order, etc

**7. Simple Dark Dungeon setup**

-Change skylight settings to create a completely dark scene
-Hover light follows player to limit visibility
-Static lights that follow player

**8. Miscellaneous Features**

-Checkpoint system
-Camera controls
-Various elevators and switches
-Sound blueprints to setup music, ambient, and voiceovers
-Flexible spawner blueprint - use to spawn a variety of actors using markers
-Ready-made tutorial widgets to display instructions as you introduce new abilities
-Raft blueprint that works with buoyancy - sail in any direction


**9. Possible Future Updates ***

-Save and load functionality
-Main menu example
-Level streaming example map


### **IMPORTANT: The project does not include any of the custom animations as they were purchased separately and cannot be distributed .**
