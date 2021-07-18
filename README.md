# Brief game interface analysis
Short essay on an analysis of a game: **Jill of the Jungle**.  
It's a trilogy of games for MS-Dos published in 1992 by Epic Megagames (current Epic Games).
Subdivided into three chapters:
- Jill of the Jungle.
- Jill Goes Underground.
- Jill Saves the Prince.  

In its simplicity, the game maintains a graphic environment that is completely consistent with each interface presented to the user.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22590804/105637423-cb49f500-5e6d-11eb-9bd3-b92b6e3a5965.png" alt="Image 1.1"/>
</p> <p align="center">Image 1.1: Jill of the Jungle home screen</b>.</p>

## Index
1. [Consistency](#Consistency)
   * [Colors](#Colors)
   * [Layout](#Layout)
   * [Level construction](#Level-construction)
   * [Simple elements](#Simple-elements)
   * [Repetition, but with skill](#Repetition-but-with-skill)
   * [Right contexts](#Right-contexts)
   * [Informative feedback](#Informative-feedback)
2. [Informative feedback](#Informative-feedback)
   * [Esc above everything](#Esc-above-everything)
   * [Dialogue with users](#Dialogue-with-users)
   * [Go back](#Go-back)
   * [Saving](#Saving)
3. [Short-term memory](#Short-term-memory)
   * [Less is more](#Less-is-more)
   * [Score Table](#Score-Table)
   * [The value of replayability ](#The-value-of-replayability )
   * [Gratification](#Gratification)
   * [I am better than you](#I-am-better-than-you)
   * [More information](#More-information)
5. [Structural Complexity](#Structural-Complexity)
    * [Simplicity requires complexity](#ISimplicity-requires-complexity)
    * [Client side](#Info-client-side)
6. [Functional Complexity](#Functional-Complexity)
   * [One purpose: to have fun](#One-purpose-to-have-fun)
7. [Complexity of use](#Complexity-of-use)
   * [Intuitive control system](#Intuitive-control-system)
8. [Written texts](#Written-texts)
   * [One font to rule them all](#One-font-to-rule-them-all)  
   * [Aggressiveness](#Aggressiveness) 
9. [Sounds](#Sounds)
   * [Main Map](#Main-Map)  
   * [Levels](#Levels) 
   * [Others](#Others) 
   * [I repeat but I learn](#I-repeat-but-I-learn) 
   * [I've heard it before](#I-'-ve-heard-it-before) 
   * [Few but good](#Few-but-good) 
10. [Animations](#Animations)   
   
# Consistency
### Colors
Jill of the Jungle uses very predominant colors in specific situations. From figure 1.1 you can see how, although the menu is not centered on the screen, it immediately stands out for its bright colors.
The **white** color structures all the information which the user can make possible choices such as the main menu, the exit menu, and information on the actions that involve pressing specific keys.  
The selection of an option is handled by the animation of a sphere of this color (*Animations are covered in the specific section: Multimedia*).  

Using different colors in the menu allows the user to distinguish the imaginary division of the choices he can make.  
For example the color **green** is used to enter a new game or restore it, the **purple** contains a series of textual information that the user can read, and so on.  

Despite its simple structure, the game contains a lot of coherence by taking advantage of the use of colors. The use of green, for example, represents a whole series of messages that express to the user changes that occur to the character such as the collection of a gem, key or a knife.  
The **blue** for expresses actions that have been performed such as opening a gate or a key unlocked door.  
The **red** commands the user must type to perform a specific external function such as opening the help menu.  
Also important is the use of the **black** color represented in the bar at the bottom of the layout. This color manages to make the player focus within the entire layout, thus distracting himself from the existence of this bar, until it shows specific written (key found, door open, and others), which immediately capture the user's attention.

### Layout
The layout structure is completely static with dynamic elements inside. Whatever the interface presented, the layout keeps *Controls, Inventory* and the title *Jill of the Jungle* unaltered.  
Although it may seem completely sparse, the static nature of these elements leads the user to memorize how they are composed, which is completely easy to remember as they have not changed over time.    

The dynamic elements break the static nature of the layout by indicating to the user information such as a life of the protagonist, level, score, elements collected and the possibility of pressing specific keys to perform certain actions (*These actions are discussed in the specific section: Complexity of use*).

### Usability
Although Jill of the Jungle represents a video game with many years behind it, the developers have tried to their limits to adapt good usability by all users.  
In 1992, personal computers were not in everyone's homes but only for a small audience. The underlying problem is not related to the type of person who bought a computer but to the concept that many of these faced the experience of a video game outside the arcade cabinets or consoles.

### Level construction
The construction of the levels almost always follows a linear trend but there are appropriate indications (Figure 2.1, black arrow) that allow the user, even novices, to understand the movement of the character.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22590804/105637718-25978580-5e6f-11eb-90db-2f1da8e8471f.png" alt="Image 2.1"/>
</p> <p align="center">Image 2.1: The arrows allow the user to understand the movements. A great affordance</b>.</p>

### Simple elements
All the elements that make up the game are represented and built in a basic way (part certainly due to the period in which Jill of the Jungle is located).  
Their visual composition allows the user to immediately understand its possible use; for example, a vine gives the player the intent to climb on, animated spikes represent an element of danger, a door with a lock icon waiting to be opened with a key, and so on.

### Repetition, but with skill
The simplicity of the elements can lead to an infinite repetition of the same, which is unfavorable for a game as it leads the user to get bored.  
To overcome this problem Jill of the Jungle implements the same elements but with different constructs based on the context. Our green vine will turn into a chain, with the same functionality, when we find ourselves inside a castle. The iron spikes will turn into the wood when we find ourselves in a dense forest.

### Right contexts
As expressed in the previous section, the elements, although repetitive, are adapted to the context. This choice is very important because it allows the user to create a sense of consistency in the levels he faces.
If you find yourself in a castle, the sense of grandeur is created by a very large number of doors to open. Similarly, in a forest, plants, bushes and other elements stand out.

# Informative feedback
Each user action corresponds to an interface response as long as the user goes to use the specified keys.

### Esc above everything
An action is always associated with the *Esc* key, whatever the interface the user is in. On the main screen (*Figure 1.1*) using the *Esc* button closes the game, in a level or in the general map allows you to return to the main menu.  
Although it may seem a trivial concept to associate the same functionality in multiple interfaces to a single key, many video games, recent and not, associate different functions to a key based on the interface or a specific context, causing problems for the user enters a learning curve that can be complex.

### Dialogue with users
Structuring the whole game in levels allows you to establish a strong connection on the concept of *start-intermediate point-end*. The user is taken to the main map, consisting of layers. Each level has its own beginning and end, no alternative.  
Once all the levels have been completed, the main map also reaches its endpoint and ends the game.

### Go back
The simplicity and the structure of the game allow the user to be able to go back, i.e. every action is reversible except the overwriting actions of previous saves.

### Saving
The user can save to any level and wherever it is located. When you restore a game, it is resumed at the exact point where it was saved.  
This can be considered an excellent strength as the user is not forced to repeat the level from the beginning, leading to a frustrating situation.

# Short-term memory
### Less is more
Jill of the Jungle cuts short-term memory overload to the bone. The commands are uniquely determined by the directional arrows and the one for the jump, all the possible elements that are collected are shown on the screen in the inventory section allowing the player not to have to remember which tools he has taken.  
Further functions such as saving, restoring, eliminating sounds and others are always shown on the screen and associated with their respective letter (pressing the letter S performs a Save, Q-Quit, R-Restore and so on).

### Score Table
The score table represents a fundamental element in many games of the past and collects the main records set by the user. Precisely for this reason, it is always proposed in the foreground in the user interface.

### The value of replayability 
A very important factor is replayability, the possibility of being able to overcome yourself by starting a new game.  
Thanks to the high score table, the player knows what his goal is, what values he must be able to reach and overcome and above all learn from his mistakes made in previous games.  
This element allows you to reconstruct an infinite loop of possible games. Despite the lack of limitation of the levels, compared to today's games (open world, DLC, and more) the player is inclined to face a new game without any possibility of finding it boring.

### Gratification
Setting a new record is also synonymous with gratification. Feeling gratified in a game pushes you to do better and better, to devise a new game plan in order to establish a higher score, and from there the gratification returns.

### I am better than you
The score table allows you to take the player to a new phase of the game. Being able to compete with friends, setting the best record of all, increases the replayability to the nth degree. Replayability and gratification, in a total immersion of players, represent the best strength of these games.

### More information
Jill of the Jungle uses OpenJill as a game engine available [here](http://www.openjill.org/doku.php).

# Structural Complexity
### Simplicity requires complexity
The game has a fairly high structural complexity. The management of all the actions of each individual character is defined by an algorithm, often reused even more than once for different characters, which must perform the same actions during a game.  
The interface has dynamic elements that are constantly updated, the character and the enemies respond reactively to every command and interaction with other objects around them, the animations are synchronized with the audio and many other aspects that in their confusion together find a profound and intense harmony that characterizes the game.  

We, therefore, learn that, in general, the algorithm defines how a specific character or object must behave.  
In Jill of the Jungle, the algorithm dictates the moves, actions, attacks of a character and how much and what damage it can cause, so how each element must interact with the game itself, with the main character and vice versa. The only exception should be made precisely for the main character himself, whose actions are managed directly by the user, even if those he can perform must necessarily (and obviously) respond to those he can perform (for example he cannot float in the air, and he cannot touch the ground without clinging to a vine, but he must necessarily walk on a flat area). It could therefore be thought that the main character requires less structural complexity than that of his enemies, as he has fewer restrictions and that he does not have to follow specific steps. This is wrong because the main character is the one who has maximum structural complexity, as he is the one who must interact directly with all aspects of a game, for example, the iteration with enemies, with obstacles, with holes, increases. statistics (following contact with a bonus) but also decreases (following a clash with an enemy).  
Although Jill of the Jungle can represent in our eyes a completely simple game, with a routine that tends to repeat itself, it contains within it complex management, which does not diminish the interlocking between each of the elements that compose it: having a sufficient vision wide of the game, we can guess how the entire structural complexity is generically high, despite being a completely smooth and linear DOS game.  

In our eyes today it could appear as something ideally simple, but if we think about what it was possible to create at the time when the video game was made, and all the actions carried out as a whole by the game itself (in particular also dependent on the number of characters present in a given level, directly proportional to the structural complexity of the level itself), we can say that it is a fairly high structural complexity.

# Functional Complexity
### One purpose: to have fun
Jill of the Jungle, despite containing a high level of structural complexity, minimizes the functional one. The purpose of the game is that of pure entertainment, as there are no additional features, elements that enrich everything, but the mere simplicity of creating a game intended for pure entertainment.

# Complexity of use
### Intuitive control system
The complexity of use represents incredibly simple ease of use. The game control system is the same as any other PC video game, which requires the use of the directional keys (therefore a factor in the majority of DOS games, and not only), and for the more advanced actions, such as saving, exit, reset and attack, are indicated which alphabetic keys to use by the legend on the sides of the game.  

All the levels offered by the game, although all different from each other, have many common factors, although the setting and the objects are different from level to level: the levels follow specific rules that apply to all levels (starting and ending point, obstacles, enemies etc ..).  
The fact that all levels functionally have many factors in common makes the complexity of use minimal, thus allowing the user to easily familiarize with the video game itself.

# Written texts
### One font to rule them all
Jill of the Jungle uses a single font to manage any communication with the user. The use of a single visual channel of communication-based on a single style manages to create in the user a sense of total satisfaction in the totality of the written objects he has to read.  

Surely the use of several different styles can make a game much more homogeneous and well done; the simple uppercase character can symbolize a sort of *scream* against the player, specific character sizes can represent attributes such as title, paragraph and others.  
We can therefore consider the use of a single font as a double-edged sword, the choice of which may depend on various factors that lead to the construction of a game (memory limits, copyright and others).

### Aggressiveness
Using an *aggressive* font (figure 6.1), devoid of slight curves, tries to get into context. What we try to express is a jungle place, of impetuous and impetuous elements ready to upset the life of the young and graceful protagonist.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22590804/105727395-52a96e00-5f2b-11eb-83b1-cb0a09a0c470.png" alt="Image 6.1"/>
</p> <p align="center">Image 6.1: Ready for the adventure?</b></p>

# Sounds
Jill of the Jungle uses audio tracks built in such a way that they can be repeated in an infinite loop.

### Main Map
The main map the player is in is devoid of any sound, at the expense of those associated with some animations.  
The elimination of a *soundtrack* allows you to build a totally safe environment, a kind of home for the player where his character can relax.

### Levels
In contrast, each level always has a piece of music associated with it. The use of silence-music between the main map and the levels creates a level for the user where he perceives that the action part of the game starts exactly as soon as a level begins and can relax once completed and returned to the game map.

### Others
Additional sounds are related to situations such as:
- The character is hit.
- The character collects an item.
- The character performs operations such as jumping, falling and others.
- Ambient sounds such as jumping frogs.
- Others.
The use of sounds allows the creation of multichannel communication with the user. For example, if the character is hit, the user will be warned by: a sound, the animation of the life bar going down, and animation to specify that the character has been hit.

### I repeat but I learn
Jill of the Jungle embodies a minimal set of sounds (effects and audio tracks). Part of this is due to the memory limit of existing machines.  
To recreate a sense of total immersion, the audio tracks are proposed in an infinite loop. Many of these have been built in such a way as to end in order to be reproduced from the beginning without the presence of appropriate amounts of silence present.  
This mechanic is a great choice in situations where technologies and memory are reduced. The user, during the game, comes to no longer perceive the repetition of the sounds, but begins to appreciate the cohesion of the level with the associated track.  

Effects are another integral part of the game. Their construction is such that, despite the effects are always the same, they do not manage to annoy the user but allow the latter to associate the action that is happening, creating a sense of uniqueness with the player.  
The player eventually gets to link the sound directly to the action without focusing on it. For example, if the main protagonist dies, the player gets to perceive it through audio without having to focus on the animation.

### I've heard it before
Each game has its own set of sounds, but all have familiarities.  
This technique is also used by Jill of the Jungle allowing the user, even a novice, to understand the scene and the context in which it is located from the sound that was emitted.  
For example, when the protagonist of the game makes a jump, although the sound can be considered totally fictitious in real life, she takes appropriate sound mechanics that are able to highlight the gesture of a jump to the user.  

The use of this technique manages to instill the player with a sense of unitary perception with all the other games, although they may be different from each 
other.

### Few but good
Jill of the Jungle is a fairly limited game in terms of memory: just think of the times in which it was developed and the few resources available, which is why some restrictions were necessary.  
Many sounds are short, played in a loop, or used in yet other sounds, without creating discomfort for the player.  

The use of these sounds allows the user to identify the game even in non-gaming environments. Sounds and effects manage to *enter* into the user's memories, even for years, and then flow into a set of memories.

# Animations
Each character has its own animation, essentially based on the sprite with which it was created. The main sprite can change and therefore evolve or transform into other characters created with different sprites, depending on certain effects or situations that occur during the game. For example, following contact with bonus items, the character can transform into another character, acquiring his abilities, and then return to the original state when passing to the next level.  
The use of transformations in Jill of the Jungle represents a breaking point with the user himself. The latter is brought to face a new vision of the game while maintaining the controls and all the information he has acquired during his games.  
The protagonist can, for example, turn into a frog, a bird or a small fish. All of these morphs mirror the mechanics of the same characters that are present in the levels. For example, if the character is transformed into a frog, she will only be able to perform the jump operation as well as all the frogs in the game.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22590804/105729006-0d863b80-5f2d-11eb-8a02-6121041e9ff2.png" alt="🕊"/>
</p> <p align="center">Jill transformed into a little bird. Does flying make you free?</b></p>



<p align="center">
  <img src="https://user-images.githubusercontent.com/22590804/105729009-0eb76880-5f2d-11eb-9308-a57352918f8a.png" alt="🐟"/>
</p> <p align="center">Brrr, how cold</b>.</p>



<p align="center">
  <img src="https://user-images.githubusercontent.com/22590804/105729011-0f4fff00-5f2d-11eb-9159-0f838f478094.png" alt="🐸"/>
</p> <p align="center">Crac crac!</b></p>
