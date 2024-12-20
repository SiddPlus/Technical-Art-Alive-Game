# Task: Fire Particle Effect

Technical Art

Sidd Ghosalkar

2304613

## Research

For this Task, I conducted extensive research on Fire Particle Effect and explored the Unreal Engine to create a more immersive experience. I prioritized studying official tutorial to develop my ability to learn new techniques independently and without direct guidance.

Additionally, I sought insights from practical tutorial and used an example of an existing game to deepen my understanding of Fire Particle Effect and ensure its proper implementation within the game.

#### Sources

###### Fire Particle Effect Unreal Engine Tutorial

"Unreal Particle Effects Tutorial", published by Epic Games on their official Unreal Engine learning platform, the source provides a comprehensive guide to creating and utilizing particle effects within the Unreal Engine. Epic Games, the developer of Unreal Engine, is widely regarded as a leader in the gaming and development industry. Their engine has powered numerous critically acclaimed games, including Fortnite and Gears of War, and has set industry standards for visual fidelity and real-time rendering. The tutorial benefits from Epic's authoritative voice and deep expertise in game development tools, ensuring that users can trust the content’s accuracy and relevance. Unreal Engine itself has won several awards for innovation and is widely adopted in game design, film production, and beyond. While the tutorial does not seem to have any notable issues, as with many technical guides, users may encounter challenges depending on their prior experience with the engine and particle systems. Nonetheless, this tutorial remains a valuable resource for beginners and professionals alike.

In reference to the current task of designing and implementing a realistic fire particle effect using Unreal Engine's Niagara or Cascade particle system, the Unreal Particle Effects Tutorial from Epic Games provides key insights into several aspects critical to achieving this goal. The tutorial explores the fundamental components of particle systems, such as emitters, materials, and behaviors, all of which are essential for creating dynamic fire effects. It also covers key parameters like particle lifetime, size, and color, which are important for simulating the flickering and fading nature of fire. Additionally, the tutorial delves into optimizing performance, an important consideration when implementing particle effects in a real-time interactive environment. Special attention is given to lighting and environmental interactions, which help enhance the realism of fire effects. These aspects will guide the development process, from basic design to more advanced techniques, ensuring the final fire particle effect is visually appealing and suitable for gameplay contexts.

I found the Unreal Particle Effects Tutorial by Epic Games to be an enjoyable and insightful resource, especially for understanding the fundamentals of particle systems. I appreciated how the tutorial was well-structured and accessible, providing clear instructions that are easy to follow, even for users who are relatively new to the engine. The emphasis on flexibility, allowing creators to choose between Niagara and Cascade, was another aspect I agreed with, as it caters to different skill levels and project needs. However, I would have liked more detailed examples or real-world applications for complex effects, as the tutorial primarily focused on the basics. While I agreed with the importance of optimizing particle systems for performance, I felt that some sections could have expanded further on advanced techniques to achieve greater realism. Overall, the tutorial was effective, but more in-depth exploration would enhance its usefulness for those seeking to push particle effects to a higher level.

###### Fire Particle Effect Motion Dreams

<iframe width="560" height="315" src="https://www.youtube.com/embed/q8avHL7syC4?si=f8slOqFZM3x1lpds" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The video titled "Fire Simulation FX in Unreal Engine Niagara" was created by UNF Games, a developer specializing in tutorials for Unreal Engine's visual effects system, Niagara. Known for concise and practical guides, UNF Games has built a reputation for helping developers implement complex visual effects efficiently. While their content has garnered positive reception for clarity and accessibility, it is primarily aimed at beginner to intermediate users of Unreal Engine. Despite their credibility within the niche, their lack of extensive industry recognition limits wider influence.

In this analysis, key aspects of the video relevant to the current task are explored. The video breaks down step-by-step methods for creating a fire particle effect, focusing on system settings, emitters, and rendering techniques. It provides insights on configuring the particle system for realism, such as adjusting velocity, lifetime, and particle size. Additionally, the video demonstrates how to add smoke and embers, emphasizing both the visual appeal and performance optimization for game environments.

I enjoyed the practical and concise approach of the video, which made implementing the fire particle effect using Niagara straightforward. The step-by-step breakdown and visual demonstrations were clear and helpful, especially for someone aiming to create a game-ready effect. However, I found that certain advanced aspects, like optimizing the effect for performance in larger environments, could have been discussed in more detail. Overall, I agree with the techniques and methods showcased, but the lack of deeper technical insight might limit its usefulness for advanced users.

###### Fire Particle Effect in Final Fantasy VII Remake

Final Fantasy VII Remake, developed by Square Enix, is a modern reimagining of the iconic 1997 role-playing game (RPG) Final Fantasy VII. Square Enix, a globally recognized developer and publisher, is known for its critically acclaimed Final Fantasy series, which has had a profound influence on the RPG genre. Final Fantasy VII Remake was highly anticipated due to the original's cultural impact and groundbreaking storytelling. Upon its release in 2020, the remake received widespread critical acclaim for its stunning visuals, engaging combat system, and expanded narrative that deepened the characters and world of Midgar. However, the game did face some criticism regarding its episodic format, with fans divided over the decision to release the story in parts. Despite this, Final Fantasy VII Remake earned numerous awards, including Best RPG at The Game Awards 2020, solidifying its place as one of the most successful modern adaptations of a classic title. Square Enix's reputation, combined with the game's overall success, outweighs any minor issues it faced during development or release.

In analyzing Final Fantasy VII Remake in relation to designing and implementing a fire particle effect in Unreal Engine, several key aspects come into focus. First, the game’s visually stunning environments and realistic effects, particularly in its combat sequences, offer inspiration for achieving lifelike fire effects. The use of dynamic lighting, particle systems, and shaders in Final Fantasy VII Remake creates immersive atmospheres, showcasing how effective fire, smoke, and energy effects can enhance the player's experience. Additionally, the fluidity and interaction of particles with the environment in the game highlight the importance of realism in particle effects, an element that will be critical when utilizing Unreal Engine's Niagara or Cascade systems. By examining how Final Fantasy VII Remake integrates its visual effects into gameplay and storytelling, one can gain insight into balancing technical detail with artistic direction, ensuring that the fire effect is both visually striking and functional within a game or interactive environment.

Overall, I thoroughly enjoyed Final Fantasy VII Remake, particularly its attention to detail in both narrative and visual design. The reimagined characters and expanded storyline added depth to the original, making the experience feel fresh while still honoring the source material. The dynamic combat system and stunning particle effects, such as fire and energy elements, were especially impressive and enhanced the overall immersion. However, I was less enthusiastic about the episodic structure of the game, as it felt incomplete without the full story. While I understand the decision to expand and elaborate on the original content, I personally would have preferred a single, cohesive release. Despite this, I agree with the critical acclaim it received for its visual achievements and its ability to modernize a beloved classic.

## Implementation

### What was the process of completing the task? What influenced your decision making?

I designed a fire particle effect that combined multiple elements to create a captivating and realistic visual. The effect included not only flames but also swirling smoke, rising embers, and subtle heat distortion, each adding depth and authenticity to the fire. By layering these elements together, I achieved a multi-faceted effect that closely mirrored the complexity of a real fire, with each component interacting naturally as they would in the real world.

To make the fire even more lifelike, I added a glow effect and adjusted the illumination to cast light on the surrounding area. This lighting allowed the fire to interact with nearby objects, casting shadows and creating a warm, flickering ambiance. The glow and illumination enhanced the realism by simulating the intensity and light output of actual flames, making the effect visually engaging and immersive within the scene.

To capture the dynamic movement of fire, I meticulously edited the emitters’ properties, tweaking variables like spawn rate, velocity, and particle lifetime to reflect the unpredictable yet flowing behavior of flames. By fine-tuning these settings, I ensured that the flames flickered naturally, the smoke rose in gradual curls, and the embers drifted sporadically, all contributing to an authentic fire simulation. This attention to detail allowed the effect to achieve a delicate balance between realism and performance, making it a standout element in my task.

## Outcome

- [Outcome Video Link](https://youtu.be/1LL87OxmXbg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/1LL87OxmXbg?si=o4PWx81vWEGzJeeS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game/tree/main)

## Critical Reflection

### What did or did not work well and why?

When I created the fire particle effect, I initially encountered an issue where the flames were facing downwards instead of rising upwards as intended. To resolve this, I adjusted the settings by turning off the gravity component within the particle system. Disabling gravity allowed the particles to move in the correct direction, achieving a more natural and realistic flame effect. This small adjustment made a significant difference in the final look of the effect. I would prefer if this task included more programming elements. While it allowed for creativity in other areas, a greater focus on coding would have made the experience more engaging and challenging. Incorporating programming would have provided opportunities to solve technical problems directly and deepen my understanding of the underlying mechanics, ultimately making the task more rewarding and aligned with my interests.

The creation of the fire particle effect went well, and I’m pleased with the results. I was able to achieve a realistic flame effect that aligned with my initial vision and the task's requirements. The process allowed me to experiment with various settings to fine-tune the look and behavior of the particles, leading to a dynamic and visually appealing outcome. Overall, it was a successful implementation that added depth to the project.

### What would you do differently next time?

I would implement the fire particle effect using Unreal Engine 5's Cascade system instead of the Niagara system to gain experience with both particle systems. While Niagara offers advanced control and customization, exploring Cascade would provide valuable insights into the foundational approach to particle effects in Unreal Engine. Working with both systems would deepen my understanding of their unique capabilities and limitations, helping me make informed choices about which tool to use in future projects.

## Bibliography

Unreal Particle Effects Tutorial | Community tutorial (2023) At: https://dev.epicgames.com/community/learning/tutorials/b8yy/unreal-engine-unreal-particle-effects-tutorial 

Fire Simulation FX in Unreal Engine Niagara | in 12 minutes (2023) At: https://www.youtube.com/watch?v=q8avHL7syC4

Final Fantasy VII Remake PS4 (2020) Developed by Creative Business Unit I and published by Square Enix

## Declared Assets
ChatGPT (s.d.) At: https://chatgpt.com: Helped rewording the dev log



