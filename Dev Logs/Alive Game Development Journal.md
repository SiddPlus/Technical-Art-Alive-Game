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

- What was the process of completing the task at hand? Did you do any initial planning?
- Did you receive any feedback from users, peers or lecturers? How did you react to it?
##### The Code & Process

###### BPC_HealthSystem

[Health System: Increase Health Function](https://blueprintue.com/blueprint/y44yuumi/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/y44yuumi/" scrolling="no" allowfullscreen></iframe>

[Health System: Decrease Health Function](https://blueprintue.com/blueprint/nl3tkw02/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/nl3tkw02/" scrolling="no" allowfullscreen></iframe>

[Health System: Event Graph](https://blueprintue.com/blueprint/g5kx_mt2/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/g5kx_mt2/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### BPC_CollectablesSystem

[Collectables System: Add Coins Function](https://blueprintue.com/blueprint/3j69m9le/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/3j69m9le/" scrolling="no" allowfullscreen></iframe>

[Collectables System: Event Graph](https://blueprintue.com/blueprint/687yzv0e/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/687yzv0e/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### Player Rolling

[Player Rolling](https://blueprintue.com/blueprint/0xk_xpj6/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/0xk_xpj6/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### Player & AI Hit

[Player & AI Hit](https://blueprintue.com/blueprint/hj2fvu0-/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/hj2fvu0-/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### WB_MainMenu

[Main Menu](https://blueprintue.com/blueprint/p1gcv9sy/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/p1gcv9sy/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### WB_SettingsMenu

[Settings Menu](https://blueprintue.com/blueprint/_73latd-/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/_73latd-/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### WB_PauseMenu

[Pause Menu](https://blueprintue.com/blueprint/75u0wwmi/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/75u0wwmi/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

[Open Pause Menu](https://blueprintue.com/blueprint/pjgd4ble/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/pjgd4ble/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### WB_RotatingPlatform

[Rotating Platform](https://blueprintue.com/blueprint/cernxw0r/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/cernxw0r/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### WB_MovingPlatform

[Moving Platform](https://blueprintue.com/blueprint/m0qvpgvj/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/m0qvpgvj/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### WB_Checkpoint

[Checkpoint](https://blueprintue.com/blueprint/nd2zp_8g/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/nd2zp_8g/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

[Player Reaches Checkpoint](https://blueprintue.com/blueprint/r2irbp27/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/r2irbp27/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### BP_Coin

[Coin Pick Up](https://blueprintue.com/blueprint/hg6p4wz1/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/hg6p4wz1/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### BP_Heart

[Heart Pick Up](https://blueprintue.com/blueprint/qsmr_2ku/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/qsmr_2ku/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### BP_Spikes

[Spikes Collision](https://blueprintue.com/blueprint/cbo0pp8m/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/cbo0pp8m/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### BP_DeathBarrier

[Death Barrier](https://blueprintue.com/blueprint/347_e0g6/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/347_e0g6/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

###### BP_End

[End Trigger](https://blueprintue.com/blueprint/x5kzgr1b/)
<iframe width="1000" height="500" src="https://blueprintue.com/render/x5kzgr1b/" scrolling="no" allowfullscreen></iframe>

(PROCESS)

##### User Feedback

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

- Did you have any issues completing the task? How did you overcome them?

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

- What did not work well? What parts of the assignment that you felt did not fit the brief or ended up being lacklustre.
- What did you think went very well? Were there any specific aspects you thought were very good?

### What would you do differently next time?

- Are there any new approaches, methodologies or different software that you wish to incorporate if you have another chance?
- Is there another aspect you believe should have been the focus?

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
