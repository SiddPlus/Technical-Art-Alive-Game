# Alive Game

Technical Art

Sidd Ghosalkar

2304613

## Research

For this project, I conducted extensive research on behaviour trees and navigation system and explored the Unreal Engine to create a more immersive experience. I prioritized studying official documentation to develop my ability to learn new techniques independently and without direct guidance.

Additionally, I used an example of an existing game to deepen my understanding of 3D platformer mechanics and ensure its proper implementation within the game.

#### Sources

###### Behavior Trees Unreal Engine

"Behavior Tree in Unreal Engine – Quick Start Guide" is an official documentation page published by Epic Games, the developer of Unreal Engine, one of the leading game development platforms globally. Epic Games is widely recognized for its robust and innovative tools, including Unreal Engine, which has been instrumental in shaping the gaming, film, and visualization industries. The documentation demonstrates Epic Games' commitment to providing accessible resources for developers of all levels, guiding them through the intricacies of Behavior Trees, a tool for creating AI logic in games. Highly regarded for its depth and clarity, the Unreal Engine documentation has earned praise from professionals and enthusiasts alike for its role in empowering creativity and technical understanding. However, some developers have noted that the guide’s dense technical language can pose challenges for newcomers, necessitating supplementary resources or community support. Despite this, the documentation remains a trusted and influential resource in the game development field.

The source explains how to create an AI system for non-player characters (NPCs) that can perform dynamic decision-making and behaviors. The guide demonstrates setting up a Behavior Tree asset and its associated Blackboard to create an AI character that can patrol, chase a player upon detection, and stop pursuit when the player is no longer visible. It covers the integration of tasks, services, and decorators in the tree to define actions and conditions, allowing for modular and flexible AI logic. This guide is essential for implementing interactive AI in games using Unreal Engine's powerful tools​

The source provided a structured and comprehensive introduction to implementing AI logic, which I found particularly enjoyable due to its clear step-by-step format. The integration of visuals and practical examples effectively simplified complex concepts, making the guide accessible to users with some prior experience in Unreal Engine. However, I felt that certain areas could benefit from more detailed explanations, especially for absolute beginners unfamiliar with AI concepts or the Behavior Tree framework. While I appreciated the focus on efficiency and functionality, I disagreed with the assumption that users would inherently understand some advanced terminologies without prior context. Overall, the guide was a valuable resource, and its strengths in clarity and practicality outweighed its minor shortcomings.

###### Navigation System Unreal Engine

"Navigation System in Unreal Engine" is provided by Epic Games, the renowned developer behind Unreal Engine, one of the most widely used game engines in the industry. Epic Games has built a reputation for creating cutting-edge tools and technologies for game development, with Unreal Engine being a cornerstone of modern game design. The documentation is a reliable and authoritative resource for developers working with Unreal Engine, reflecting the company's commitment to providing comprehensive and up-to-date information. Epic Games has received numerous accolades for Unreal Engine, including awards for its groundbreaking contributions to the gaming and interactive media industries. The Navigation System documentation, specifically, plays a crucial role in guiding developers through the creation of AI pathfinding and navigation solutions within games, a fundamental aspect of game design. While generally well-regarded for its technical depth and clarity, the documentation can sometimes be overwhelming for beginners due to the complexity of the engine's systems, and occasional updates may lead to slight inconsistencies in older content. Nevertheless, Epic Games' continued support and regular updates ensure that the source remains a vital reference for professionals in the field.

The source provides tools for creating AI pathfinding and navigation capabilities within a project. Central to this system is the Navigation Mesh (NavMesh), a data structure that defines areas navigable by AI agents, generated based on the geometry of the environment. The system supports features like dynamic pathfinding, avoidance mechanisms, and agent-specific navigation settings. It allows customization through components, query filters, and project settings, enabling optimization for performance and adaptability to different scenarios. The system also integrates with Unreal Engine’s AI framework, facilitating realistic movement behaviors​.

I found the "Navigation System in Unreal Engine" documentation from Epic Games to be an invaluable resource for understanding how to implement AI pathfinding and navigation within Unreal Engine. The depth of information provided, from basic concepts to advanced techniques, makes it an excellent reference for both beginners and seasoned developers. I particularly appreciated the clear explanations and the practical examples that help to demystify the complexities of navigation meshes and AI behavior. However, I did find some sections to be dense with technical jargon, which could make it challenging for newcomers to fully grasp the material without additional context. While I agree with the overall accuracy and usefulness of the content, I think more beginner-friendly examples and a clearer breakdown of the concepts could improve the accessibility for those less familiar with Unreal Engine. Nonetheless, the source offers a thorough, authoritative guide that is undeniably helpful for anyone looking to work with the navigation system in Unreal Engine.

###### Super Mario Galaxy

Nintendo’s Super Mario Galaxy, developed by Nintendo EAD Tokyo and released in 2007, is one of the most acclaimed entries in the iconic Super Mario series. Directed by Yoshiaki Koizumi and produced by Shigeru Miyamoto, the game received widespread critical acclaim for its innovative gameplay, unique gravitational mechanics, and visually stunning design. Its development showcased Nintendo's dedication to pushing the boundaries of 3D platforming, particularly with its creative use of physics and planetary exploration. Super Mario Galaxy received numerous awards, including Game of the Year from several publications, and is often considered one of the greatest video games of all time. Although it was technically ambitious, its launch was smooth and devoid of major technical issues, setting a high standard for the franchise and for games on the Wii console.

Super Mario Galaxy introduces unique gameplay mechanics centered around gravity and spherical platforming, distinguishing it from previous Mario titles. Players navigate Mario across small, planetoid-like environments, each with its own gravitational pull, allowing him to run upside-down and around curves in ways not seen in traditional platformers. The game's core mechanics include precise platforming, jumping, and combat, with Mario equipped with familiar moves like the triple jump, ground pound, and spin attack, which helps him interact with objects and defeat enemies. Additionally, the game incorporates motion controls via the Wii Remote, allowing players to collect “Star Bits” (used as in-game currency) and execute various actions, like aiming to shoot Star Bits at foes. Mario's journey takes him through a variety of themed galaxies, each with distinct gravity-based puzzles, environmental hazards, and level design challenges that exploit the 3D spherical landscapes. These mechanics, combined with gravity-defying platforming, create a fresh, immersive experience within the Mario universe, elevating traditional platforming with spatial dynamics.

Playing Super Mario Galaxy was an unforgettable experience, primarily due to its imaginative level design and unique gravity mechanics, which transformed familiar platforming gameplay into something fresh and exhilarating. I particularly enjoyed how the game balanced accessible controls with complex environments, keeping the gameplay consistently engaging without overwhelming players. The use of gravity as a core mechanic was both innovative and well-executed, making exploration feel intuitive yet challenging. However, while the motion controls were an interesting addition, there were moments when they felt slightly gimmicky or unnecessary, particularly when aiming Star Bits at enemies. Overall, I agree with the widespread praise for Super Mario Galaxy—its ambitious design, polished mechanics, and the sheer joy of discovery make it a landmark in gaming. The game’s impact and Nintendo’s inventive approach more than justify its reputation as a modern classic.

## Implementation

### What was the process of completing the task? What influenced your decision making?

##### The Code & Process

- What was the process of completing the task at hand? Did you do any initial planning?

###### BPC_HealthSystem

[Health System: Increase Health Function](https://blueprintue.com/blueprint/y44yuumi/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/y44yuumi/" scrolling="no" allowfullscreen></iframe>

[Health System: Decrease Health Function](https://blueprintue.com/blueprint/nl3tkw02/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/nl3tkw02/" scrolling="no" allowfullscreen></iframe>

[Health System: Event Graph](https://blueprintue.com/blueprint/g5kx_mt2/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/g5kx_mt2/" scrolling="no" allowfullscreen></iframe>

To implement the health system for the player, I developed an actor component dedicated to managing health functionality. This actor component ensures a modular approach, making it easier to reuse or extend in the future. Within the component, I created two core functions to handle health modifications: one for increasing health when the player gets healed and another for decreasing health when they take damage. These functions streamline the health management process, keeping the logic organized and encapsulated.

Both functions include updates to the UI to reflect changes in real-time. Whenever the player's health increases or decreases, the health bar on the UI dynamically adjusts to provide immediate feedback. This integration enhances the player experience by keeping them informed about their current health status without relying on external cues or distractions. Ensuring the UI synchronizes seamlessly with gameplay was a crucial focus of this system.

Additionally, I initialized the health bar UI value in the event graph at the start of the game. This step ensures that the health bar displays the correct value from the beginning, avoiding any inconsistencies or confusion. By setting the health bar's initial value and coupling it with the actor component's functions, I achieved a cohesive and responsive health system for the player.

###### BPC_CollectablesSystem

[Collectables System: Add Coins Function](https://blueprintue.com/blueprint/3j69m9le/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/3j69m9le/" scrolling="no" allowfullscreen></iframe>

[Collectables System: Event Graph](https://blueprintue.com/blueprint/687yzv0e/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/687yzv0e/" scrolling="no" allowfullscreen></iframe>

To implement the collectible system for the player, I developed an actor component designed specifically to manage coin pickups. This component provides a centralized structure for tracking the player's collected coins, ensuring consistency and scalability across the game. Within the component, I created a function that adds coins to the player's wallet whenever they interact with a coin actor in the level. This streamlined approach simplifies the management of collectible items and keeps the code modular.

The function not only updates the player's wallet but also dynamically updates the UI to reflect the current coin count. Whenever a coin is collected, the coin text on the UI is immediately refreshed to display the updated total. This real-time feedback ensures the player is always aware of their progress, enhancing immersion and providing a satisfying sense of reward for each collectible picked up.

To initialize the system, I set the coin text UI value in the event graph at the start of the game. This step ensures that the UI accurately displays the initial coin count, avoiding any discrepancies or confusion during gameplay. By combining the initialization step with the actor component's functionality, I achieved a cohesive and responsive collectible system that seamlessly integrates with the player experience.

###### Player Rolling

[Player Rolling](https://blueprintue.com/blueprint/0xk_xpj6/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/0xk_xpj6/" scrolling="no" allowfullscreen></iframe>

To implement a rolling mechanic for the player character, I began by creating an input action and mapping it to the left control key. This allowed me to define a specific input for triggering the roll. In the event graph of the third-person character blueprint, I added the enhanced input action node to handle the input event. This setup provides a responsive framework for executing the rolling mechanic based on player input.

Next, I implemented logic to check the player's current state before initiating the roll. The first condition verifies if the player is not already rolling to prevent overlapping animations or unintended behavior. If this condition is true, the second check determines whether the player is currently attacking. These conditions are crucial for ensuring that the roll mechanic interacts seamlessly with other gameplay systems and animations.

Depending on the outcomes of the conditions, the appropriate action is taken. If the player is not rolling and not attacking, the roll action is initiated. However, if the player is in the middle of an attack, the roll cancels the current attack instead of executing normally. This dual functionality adds depth to the system by allowing the roll to serve both as a movement option and a strategic tool to interrupt attacks when necessary.

###### Player & AI Hit

[Player & AI Hit](https://blueprintue.com/blueprint/hj2fvu0-/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/hj2fvu0-/" scrolling="no" allowfullscreen></iframe>

To enhance character interactivity, I implemented two custom events: Reaction and Die. The Reaction event handles responses to being hit by playing a hit reaction sound and triggering a hit reaction animation montage. Additionally, this event moves the character backward, simulating the physical impact of the hit. This setup provides immediate feedback to players and adds realism to combat interactions.

The Die event focuses on handling the character’s death. For the player character, it disables input to prevent further actions and sets physics simulation to true, allowing for dynamic interactions with the environment upon death. Additionally, it resets the level for the player, ensuring a smooth transition to restart gameplay. These features create a clear distinction between being damaged and dying, enhancing the overall gameplay flow.

To integrate these events, I used the Event Any Damage node to monitor when the character takes damage. Upon taking damage, the system decreases the character’s health and calls the Reaction custom event. Finally, it checks if the character’s health has reached zero, indicating death. If so, the Die custom event is triggered. This sequence ensures a cohesive and responsive system for handling damage, reactions, and death events in the game.

###### Player Camera Zoom In/Out

[Player Camera Zoom In/Out](https://blueprintue.com/blueprint/841cwtmn/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/841cwtmn/" scrolling="no" allowfullscreen></iframe>

First, I began by creating an input action in the project and assigned an action value to it, which I then mapped to the scroll wheel. This input action allowed the player to control the camera zoom by scrolling. Mapping it to the scroll wheel provided an intuitive and responsive way for players to adjust their view of the character.

Next, I multiplied the action value by -100, which allowed for the zooming effect to be more pronounced with each scroll. I then added the result of this multiplication to the camera boom's target arm length, controlling the camera's distance from the player character. By doing this, I was able to adjust the camera's positioning dynamically based on the player's input.

Finally, I clamped the target arm length to a minimum value of 50 and a maximum value of 1000 to ensure that the camera wouldn't zoom too far in or out. Setting the target arm length in this way provided a smooth and controlled zooming mechanic, allowing players to easily zoom in and out from the player character while maintaining an optimal viewing distance.

###### Power Up

[Power Up](https://blueprintue.com/blueprint/ag34zmv5/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/ag34zmv5/" scrolling="no" allowfullscreen></iframe>

[Power Up Active](https://blueprintue.com/blueprint/645v7_7x/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/645v7_7x/" scrolling="no" allowfullscreen></iframe>

First, I added a sphere collider to the power-up object and implemented functionality to detect player collisions. When the player collided with the power-up, I set the IsActive variable to true, updated the damage value to 2, and ensured the power-up's visibility was enabled. After these changes, I destroyed the power-up actor to indicate that it had been collected.

Next, in the Event Tick function, I added logic to monitor the state of the IsActive variable. If IsActive was true, I utilized a time-tracking variable and incremented it with Delta Seconds from each frame. This updated time value allowed me to track how long the power-up effects were active in real-time.

Finally, I checked whether the tracked time reached or exceeded 10 seconds. If so, I reset the power-up's effects by setting IsActive back to false, returning the damage value to its default of 1, and disabling the visibility of the power-up. This ensured that the power-up's effects were temporary and would revert after the designated duration.

###### UI

[Main Menu](https://blueprintue.com/blueprint/p1gcv9sy/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/p1gcv9sy/" scrolling="no" allowfullscreen></iframe>

[Settings Menu](https://blueprintue.com/blueprint/_73latd-/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/_73latd-/" scrolling="no" allowfullscreen></iframe>

[Pause Menu](https://blueprintue.com/blueprint/75u0wwmi/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/75u0wwmi/" scrolling="no" allowfullscreen></iframe>

[Open Pause Menu](https://blueprintue.com/blueprint/pjgd4ble/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/pjgd4ble/" scrolling="no" allowfullscreen></iframe>

I created four widget blueprints to enhance the player's interaction with the game. The first is the Main Menu, which serves as the entry point for the player. From here, they can choose to play the game, access the settings menu, or exit the game entirely. This menu is designed to provide an intuitive and straightforward navigation experience for the player.

The second widget blueprint is the Loading Screen, which appears when the player clicks "Play Game" from the main menu. This screen helps bridge the transition into the gameplay environment, ensuring the player understands that the game is actively loading. It improves the overall user experience by reducing any potential confusion during this process.

The third widget blueprint is the Pause Menu, which allows players to pause the game when needed. From this menu, they can choose to resume gameplay, return to the main menu, or quit the game entirely. Lastly, the Settings Menu offers a range of customization options. Players can switch between windowed and fullscreen modes, select from five resolution options, adjust graphics quality across five presets, and toggle V-Sync on or off. These settings provide players with the flexibility to tailor the game to their preferences and hardware capabilities.

###### BP_RotatingPlatform

[Rotating Platform](https://blueprintue.com/blueprint/cernxw0r/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/cernxw0r/" scrolling="no" allowfullscreen></iframe>

In the User Construction Script, I set up the functionality to customize the rotation of the object by accessing the Rotating Movement Component node. This component is responsible for defining the rotational behavior of the actor. By configuring its rotation settings in the construction script, I ensured that the changes take effect immediately and are visible during the design phase.

To make the rotation adjustable, I introduced a variable for the rotation rate. This variable determines how quickly the object rotates and can be easily modified in the scene view. By exposing it to the editor, I provided a user-friendly way to tweak the rotation speed without needing to dive into the script, which is particularly useful for testing and fine-tuning.

This approach enhances flexibility and streamlines the design process. Designers or developers can quickly adjust the rotation rate to suit different gameplay scenarios or aesthetic requirements. By centralizing the rotation logic in the User Construction Script, the setup remains organized and efficient, ensuring consistent and predictable behavior.

###### BP_MovingPlatform

[Moving Platform](https://blueprintue.com/blueprint/m0qvpgvj/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/m0qvpgvj/" scrolling="no" allowfullscreen></iframe>

 In the User Construction Script, I utilized the Interp To Movement Component node to set up movement behavior for the actor. This component allows the actor to interpolate smoothly between specified points, creating dynamic and customizable movement. To define the movement path, I added two Control Point Position nodes, which determine the starting and ending points of the interpolation.

The first control point position was set to (0, 0, 0), establishing a fixed starting location for the movement. This ensures that the movement always begins from a consistent and predictable position. For the second control point, I created a variable for its position, which I exposed in the scene view. This variable makes it easy to modify the endpoint of the movement path directly within the editor, offering a practical and efficient way to adjust the actor’s behavior during design.

By combining these elements, I created a system that provides flexibility and ease of customization for the movement paths. Designers or developers can adjust the variable for the second control point to tailor the interpolation to suit specific gameplay needs or aesthetic requirements. This approach not only enhances efficiency during development but also ensures the movement remains adaptable to different scenarios.

###### BP_Checkpoint

[Checkpoint](https://blueprintue.com/blueprint/nd2zp_8g/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/nd2zp_8g/" scrolling="no" allowfullscreen></iframe>

[Player Reaches Checkpoint](https://blueprintue.com/blueprint/r2irbp27/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/r2irbp27/" scrolling="no" allowfullscreen></iframe>

In the On Component Begin Overlap node, I set up a system to ensure the checkpoint reacts when colliding with the player. Upon detecting the collision, I played a sound to provide immediate feedback, signifying that the checkpoint had been activated. Then, I updated the respawn transform to match the checkpoint's location and set the checkpoint's state to "on" by marking a variable as true. To visually indicate that the checkpoint had been used, I hid the static mesh of the checkpoint in the scene.

When the player reaches a checkpoint, the system verifies whether the checkpoint is active. If the checkpoint is "on," I reset the player's position and rotation to match the stored respawn transform, effectively moving them back to the checkpoint. This functionality ensures the player respawns at the correct location after triggering the checkpoint, streamlining the respawn process for seamless gameplay.

After repositioning the player, I enabled their input and set simulated physics to false, allowing the player to regain control and continue playing. This sequence of events ensures that checkpoints function as intended, providing both a visual and functional system for respawning, enhancing the player's experience and supporting smoother gameplay progression.

###### BP_Coin

[Coin Pick Up](https://blueprintue.com/blueprint/hg6p4wz1/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/hg6p4wz1/" scrolling="no" allowfullscreen></iframe>

In the Event Tick, I implemented functionality to make the actor continuously rotate by adding relative rotation. This rotation was set to increase by 1.5 degrees on the Z-axis during each tick, creating a smooth and consistent spinning motion. This visual effect adds dynamism to the actor, making it more noticeable and engaging for the player during gameplay.

To handle interactions, I used the On Component Begin Overlap node to detect when the player collided with the actor. The node checks for overlap events and determines whether the colliding entity is the player. This ensures that only the player’s interactions trigger the following sequence of events, maintaining clear and purposeful gameplay behavior.

When a collision with the player occurred, I added a coin to the player’s total, providing a tangible reward for the interaction. To enhance the experience, I played a pickup sound, offering audio feedback to reinforce the action. Finally, I destroyed the actor, removing it from the scene to signify that it had been collected. This sequence creates a satisfying and intuitive system for handling collectible items in the game.

###### BP_Heart

[Heart Pick Up](https://blueprintue.com/blueprint/qsmr_2ku/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/qsmr_2ku/" scrolling="no" allowfullscreen></iframe>

In the Event Tick, I implemented functionality to make the actor continuously rotate by adding relative rotation. This rotation was set to increase by 1.5 degrees on the Z-axis during each tick, creating a smooth and consistent spinning motion. This visual effect makes the actor more noticeable and draws attention to the health pickup, encouraging the player to interact with it during gameplay.

To handle interactions, I used the On Component Begin Overlap node to detect when the player collided with the actor. The node checks for overlap events and ensures that the colliding entity is the player. This targeted detection ensures that only the player can interact with the health pickup, maintaining proper gameplay mechanics.

When the player collided with the health pickup, I increased the player's health, providing a health boost as a reward for the interaction. To enhance the experience, I played a pickup sound, offering audio feedback to reinforce the action. Finally, I destroyed the actor, removing it from the scene to signify that it had been collected. This sequence creates a satisfying and intuitive system for handling health pickups in the game.

###### BP_Spikes

[Spikes Collision](https://blueprintue.com/blueprint/cbo0pp8m/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/cbo0pp8m/" scrolling="no" allowfullscreen></iframe>

In the On Component Begin Overlap node, I first checked if the player collided with the actor. If the collision was detected, I set the IsColliding variable to true, indicating that the player is in contact with the actor. Afterward, I applied damage to the player and moved them back, creating a reaction to the collision. This ensures that the player takes damage and is pushed away from the source of the collision, providing feedback that something harmful has occurred.

Additionally, I implemented a check to see if the player was still colliding. If the player remained in contact with the actor, the system would loop back and reapply damage, continuously harming the player while they stay in the collision area. This mechanic creates a persistent effect, ensuring that the player cannot avoid taking damage while in the active collision zone.

In the On Component End Overlap node, I checked if the player was no longer colliding with the actor. If the player had moved out of the collision range, I set the IsColliding variable to false, stopping any further damage application. This helps ensure that damage is only applied while the player remains in the danger zone, making the system responsive and balanced.

###### BP_DeathBarrier

[Death Barrier](https://blueprintue.com/blueprint/347_e0g6/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/347_e0g6/" scrolling="no" allowfullscreen></iframe>

In the On Component Begin Overlap node, I implemented a check to detect if the actor collided with the player. This verification ensures that only the player triggers the event, maintaining specificity in the interaction. The system identifies the player as the target of the collision and initiates the next steps in response to the event.

Upon detecting the player, I applied damage to reduce their health. The amount of damage applied could lead to the player's death if their health reaches zero. This mechanic introduces stakes to the gameplay, ensuring that the player must navigate carefully to avoid hazardous elements and preserve their health.

By incorporating this mechanic, the game establishes a clear consequence for falling or colliding with dangerous actors. This not only adds a layer of challenge but also encourages players to be mindful of their surroundings. The system enhances the overall gameplay experience by creating a balance of risk and reward, keeping the player engaged and motivated to proceed with caution.

###### BP_End

[End Trigger](https://blueprintue.com/blueprint/x5kzgr1b/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/x5kzgr1b/" scrolling="no" allowfullscreen></iframe>

In the On Component Begin Overlap node, I set it up so that when the player reaches the end, the game ends.

###### Day & Night Cycle

[Day & Night](https://blueprintue.com/blueprint/30nq-36q/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/30nq-36q/" scrolling="no" allowfullscreen></iframe>

First, I calculated the sun's rotation around the world using delta seconds to determine the transitions between day and night. This rotation forms the basis for simulating realistic lighting changes, marking when it is dark and when it is light. By leveraging delta seconds, I ensured that the transition aligns smoothly with the passage of time in the game world.

For the transition from day to night, I used linear interpolation (lerp) to gradually shift the sun's intensity and color. I interpolated between the highest intensity value and the lowest intensity value to create a dimming effect as daylight fades. Simultaneously, I adjusted the color, transitioning from the lightest hues of day to the darkest shades of night, ensuring a natural and seamless shift in the environment.

Similarly, for the transition from night to day, I applied the same lerping process but in reverse. I interpolated between the lowest intensity value and the highest, mimicking the gradual brightening as the sun rises. The color also shifted from the darkest hues of night to the lightest colors of day. These smooth transitions created a dynamic day-night cycle that enhances the game's atmosphere and immersion.

##### User Feedback

I received feedback from my lecturer, who had an overall positive reaction to the game. He highlighted that the level was engaging, describing it as both fun and challenging, which affirmed that the design captured the desired level of difficulty. This feedback was encouraging and provided a solid foundation to refine the gameplay experience further.

One suggestion was to improve the animations by separating the jump and fall animations. The lecturer pointed out that having a dedicated falling animation would make the gameplay feel more polished and immersive, as it would better reflect the player’s actions. Additionally, he recommended adding an icon to the coin UI to enhance its visual clarity and make it more intuitive for players to track their collectibles.

Another suggestion was to reposition the health bar to the bottom middle of the screen. This adjustment would make it easier for players to monitor their health during gameplay without breaking focus. Lastly, the lecturer emphasized the importance of addressing existing bugs, advising me to prioritize fixing these issues before adding new features. This approach ensures a smoother and more enjoyable experience for the player.

Another suggestion for improving gameplay is to compress and shorten the player's attack animations, ensuring that combat feels more fluid and responsive. Shorter animations can make actions feel snappier, reducing delays and enhancing the overall combat experience. This adjustment would help players feel more engaged during fights and maintain a steady game pace.

Another recommendation is to include a loading screen when transitioning into the game. A clear loading screen not only improves the user interface but also signals to the player that the game is preparing to load, setting expectations and preventing confusion. It can also be an opportunity to provide helpful tips or lore to enhance the player's immersion during downtime.

Another suggestion is to add blood splatter effects whenever the sword collides with either the player or an enemy. This visual feedback would make combat feel more impactful, clearly indicating when the sword has successfully struck its target. The blood splatter would enhance the realism of the battle and increase the intensity of the player's experience.

Another suggestion is to incorporate ambiance into the environment to further immerse the player. implement this through background sounds. Adding ambiance would make the game world feel more alive and engaging, drawing players deeper into the experience.

Lastly, allowing players to zoom the camera in and out from their character would give them more control over their perspective. This feature could be particularly useful for tailoring the experience to individual preferences, whether players want a closer, more immersive view or a wider angle to better assess their surroundings. Camera flexibility can significantly enhance player satisfaction and accessibility.

## Outcome

- [Example Video Link](https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstley)
- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game/tree/main)
- [Example Build Link](https://samperson.itch.io/desktop-goose)

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ?si=C4v0qHaYuEISAC01" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Figure 3. An example of an embedded video using a HTML code snippet.*

<iframe frameborder="0" src="https://itch.io/embed/2374819" width="552" height="167"><a href="https://bitboyb.itch.io/nephilim-resurrection">Nephilim Resurrection (BETA) by bitboyb</a></iframe>

*Figure 4. An example of a itch.io widget*

## Critical Reflection

### What did or did not work well and why?

One problem I ran into is that when enemy's sword didn't do damage all the time, to solve I checked the sphere trace with player pawn instead of player tag. Another problem is when player's sword didn't do damage, to solve [].

The progression from the development stage to the polish stage went very well. Each phase was executed smoothly, with consistent improvements made to the game's mechanics, visuals, and overall experience. This seamless transition ensured that all aspects of the game were refined and cohesive by the time it reached the due date.

### What would you do differently next time?

If I were to approach this project differently, I would have chosen to create a game in a genre other than a platformer. Exploring a different genre could have opened up new possibilities for gameplay mechanics and player engagement, allowing me to experiment with unique design elements and challenges outside the typical platforming framework.

## Bibliography

Behavior Tree in Unreal Engine - Quick Start Guide | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/behavior-tree-in-unreal-engine---quick-start-guide 

Navigation System in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/navigation-system-in-unreal-engine 

Super Mario Galaxy Nintendo Wii (2007) Developed by Nintendo EAD Tokyo and published by Nintendo

## Declared Assets

Soul City: Fab (s.d.) At: https://www.fab.com/listings/dd77fee6-0ad2-41ce-b32c-09300c24c9f3

Spike Trap 01 - Download Free 3D model by Nichgon (2021) At: https://sketchfab.com/models/4022678cac214fd2963894aa152fc6f2/embed?autostart=1

Props Heart - Download Free 3D model by Alexandra Arzamazova (@a9646542086) (2024) At: https://sketchfab.com/models/852122c1055e44c78ba0016329f67853/embed?autostart=1

Power Up - Download Free 3D model by Trockk (@Timrockk) (2024) At: https://sketchfab.com/models/fab43f5440f54143a015f2ed25f1d692/embed?autostart=1

acasas (2018) 3d Pirate Coin. [Image] At: https://opengameart.org/content/3d-pirate-coin

Sword - Download Free 3D model by minghauLoh (@minghau) (2016) At: https://sketchfab.com/models/07463a2658e04d6ab8a42b5639a35d63/embed?autostart=1
 
Mixamo Characters: Alien Soldier & Swat Guy

Mixamo Animations: Idle, Ninja Run, Fast Run, Standing Jumping, Sprinting Foward Roll, Hit Reaction, One Hand Sword Combo, Stable Sword Inward Slash & Stable Sword Outward Slash

Pixabay: Battle of the Dragons, Footstep 1,  Grunt 1, Hit Swing Sword Small 2, Item Equip, Ping

```Markdown
# General Tips

- Use plenty of images and videos to demonstrate your point. You can embed YouTube tutorials, your own recordings, etc.
- Always reference! Even documentation, tutorials and anything you used for your assignment. Use an inline reference for the sentence and a bibliography reference at the end.
- Word count is not important, you can also chose to use bullet points. As long as it is clear and readable, the format your decide to use can be flexible.
- You are free to use AI but please ensure you have made a note in the declared assets, for example if you have a script called Test.cs , you should note that AI was used to in the creation of this script. You can use a bullet point list for each asset used like:

The following assets were created or modified with the use of GPT 4o:
- Test.cs
- AnotherScript.cs
- Development Journal.html

```
