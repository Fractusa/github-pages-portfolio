# Hello, I'm André Christensen

Welcome to my webpage!

I'm a **Computer Science Student**.

---

## About Me
- 
- 
- 
- 

---

## Skills
- **Languages:** C#, HTML
- **Frameworks:** Blazor, .NET
- **Tools:** Git, Visual Studio, VS Code

---

## Portfolio - Project Game 2025
### Update 1
Researching different Game Engines, for potential use in game programming; Unity chosen. Brainstorming features and ideas for game content, as well as researching courses for Unity for learning.

### Update 2
Following Unity Courses to learn about Unity functionality. Started development on Project Game, adding basic tilemap functionality and PlayerController script with Movement implemented using Unity's InputAction.

### Update 3
Worked with Unity Animations, adding a running animation to the Player. Added attack functionality to the Player, enabling it to be able to shoot Projectiles. Added different Collectibles that enemies drop on death, namely experience (always) and health (random).
Started work on an Experience System allowing the player to gain experience from killing enemies, and later through this give the ability to choose new abilities and/or stat increases. 
Finally created basic functionality towards adding new abilities and effects. Abilities being full fledged with multiple effects eg. Fireball (Effects: Projectile, Burning, Damage etc.) while effects are smaller blocks that abiltiies are built from.

A few difficulties making scripts work together correctly, sometimes not using the same instance of a script eg. PlayerController & PlayerHealth scripts not using the same Stats for the Player. Otherwise mostly basic functionality for now.

### Update 4
Fixed Performance Issues when too many enemies are present at the same time. Seemed to be a Physics issue, where colliders between enemies continued to interact between each other, causing massive lag spikes. 
Solution was to add an Enemy Layer and edit Layer Collision between enemies to disabled, effectively ignoring Physics between Enemies. This might be a temporary solution, but resolved the issues for the moment. 

Created a new Ability system, where multiple effects eg. Projectile Cast, Burn, AoE, Scattershot can be attached, giving the player the opportunity to create unique abilities. 
So far only a Simple Projectile ability which autofires towards closest enemy, has been implemented. 
The idea is to create a bunch of different effects and have the player craft their own abilities throughout the run. 

Finally time has been spent cleaning up a bit of the code, fixing minor bugs, writing comments as well as looking at asset creation using Aseprite. 

### Update 5
A bit slower week, but added functionality for upgrading abilities so far only for 1 effect, but is easily expanded on as effects are added.
Otherwise have been finalizing custom assets for the game using Aseprite - 3 different projectiles as well as 4 different collectible drops.
Started work on creating a player character, find it hard to work in detail as well as creating animations for running etc. Created a very simple character for now, can be expanded on later.

### Update 6
Finding trouble using the Ability system, since it's based on Scriptable Objects, I have to pass through ability data such as Pierces, Explosion Radius etc. to every ability, in order to be able to upgrade this.
Scriptable Objects however still wins in terms of flexibility; they can be attached to multiple characters if necessary and/or reused for enemy abilities.

An alternative would be to use Mono Behaviours, where the script is simply attached to the GameObject in our game it would be the Player. Where all ability logic lies within the script for each ability, albeit
I am unaware about the possibility to add new abilities during runtime to the Player through this. The alternative could prove easier to use, especially for the size of our game, losing the extra potentially unnecessary complexity.

### Update 7
Started work on implementing a backend for the game, herein I'd like to look at:
* Player accounts to track our roguelite elements of a currency earned throughout the runs.
* Leaderboard where either a score is submitted when a run ends and/or enemies killed is submitted - ideally viewable through the game otherwise through a webapp.
* Stats tracking wherein stats such as time played, enemies killed and the sorts are tracked and added to a total number, to see how active the game is.
Research for this has begun, and implementation will begin in the following days. 

---

## Past Projects
### ✈ Flight & Hotel Search App
[🔗 View Project](https://yourusername.github.io/flight-hotel-app)  
A Blazor Server app that fetches flight and hotel data from a custom ASP.NET Core Web API.  
**Tech:** C#, .NET, Blazor, REST API

---

## Contact
- **Email:** ehris12@hotmail.com
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/andr%C3%A9christensen/)
- **GitHub:** [GitHub](https://github.com/Fractusa)
