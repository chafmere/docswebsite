+++
author = "Chafmere"
date = 2024-03-16
title = "Making Spray Patterns"
image = "/images/spray_pattrerns.png"
+++

When Making an FPS Game, the handling of weapon spray is a crucial aspect that can greatly impact gameplay. Some games use spray patterns as a skill-based mechanic, while others opt for a more random approach simply for immersion.

One of the most notable examples of a skill-based spray system is found in Counter-Strike, where players can memorize spray patterns to improve their accuracy. Other games like Valorant and Rainbow Six Siege also feature similar systems. On the other hand, games like Fortnite or Halo utilize more random spray patterns, which can be less satisfying for players seeking a skill-based challenge.

Implementing a spray system involves several steps.A projectile component is created to perform raycasting, with a spread variable influencing the end point of the ray. The use of Spray Profiles allows for modular and convenient spray pattern creation, enhancing prototyping efficiency.

For a predetermined path we can utilize tools like path2d or curve to create a path for the spread to follow with each successive shot.For random spray patterns, a noise function is used to introduce variation. This noise is multiplied by the shot count, creating a progressively larger area of dispersion.

True randomization can be achieved by changing the noise seed every shot. Combining both skill-based and random elements can lead to dynamic and engaging gameplay experiences in FPS games. Watch the Full Video Here!

{{< youtube "https://www.youtube.com/watch?v=djsEgUXfChQ&feature=youtu.be" >}}


Don't forget to check out the [Godot 4 FPS Template](https://chaffgames.com/fps-game-template/)!