# Task: Single Layer Water Material

Technical Art

Sidd Ghosalkar

2304613

## Research

- What type of sources did you identity and want to explore? How would you justify it in reference to the brief set? Think about the focus of the brief.
- What type of sources do you want to avoid? How could these kinds of sources be detrimental to the user experience, immersion or implementation?

#### Sources

- An opening paragraph about the source stating the author, developer or organisation, this paragraph should explain the source's influence, credentials, critical reception, awards, reputation or any issues with the source. For example, if the source is not reputable. If the source is a game, the issues that occurred during development or if had a poor launch.
- List the aspects analysed in reference to the current task.
- An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.

###### Single Layer Water Material Unreal Engine Documentation

"Single Layer Water Shading Model" is part of the official Unreal Engine documentation provided by Epic Games. As a cornerstone in the game development industry, Epic Games is highly regarded for its contributions to real-time 3D creation, particularly through Unreal Engine, which has been widely praised for its cutting-edge graphics, advanced physics, and versatile tools. The documentation serves as an authoritative resource, offering in-depth technical explanations and implementation guidelines, directly supported by Epic Games' expertise. Unreal Engine’s documentation is well-received by developers and industry professionals for its clarity and comprehensive coverage of topics, making it a key source of information for both novice and experienced developers. However, some users have critiqued the documentation for occasionally lacking in detailed examples or troubleshooting guidance, which can pose challenges for those unfamiliar with specific tools or functions. Despite this, the documentation remains a crucial reference point for developers working with Unreal Engine.

In reference to the current task of creating a single-layer water material in Unreal Engine, several key aspects are analyzed based on the official documentation. These include the handling of reflection to ensure realistic light bounce on the water surface and refraction, which simulates light bending through the water for a convincing visual effect. The task also examines surface movement, providing techniques to simulate dynamic effects like ripples and waves for enhanced realism. Additionally, light interaction is a critical aspect, focusing on how the water material handles translucency, shadow casting, and caustics to achieve natural light behavior. Performance optimization is equally important, with guidelines on creating a visually compelling material that remains efficient for real-time rendering. Finally, the effective use of Unreal Engine's Material Editor is discussed, highlighting how to implement and adjust these properties to create a realistic and performance-optimized water material.

I appreciated the clarity and depth of the Unreal Engine documentation on the Single Layer Water Shading Model. It provided detailed insights into key concepts like reflection, refraction, and light interaction, which are essential for creating visually compelling water materials. I particularly enjoyed the straightforward explanations and the practical examples, which made implementing surface movement and optimizing performance much easier. However, I felt that the documentation could benefit from more troubleshooting tips or advanced use cases, as some areas lacked deeper explanations for complex scenarios. Overall, I agree with the methods and techniques outlined in the source, though I would have preferred additional guidance on addressing potential challenges developers might face during implementation.

###### Single Layer Water Material World of Level Design

"Materials Starter Content: Water Instance" is published on World of Level Design, a well-regarded platform dedicated to providing resources and tutorials for game developers and level designers. Founded by the experienced designer and educator, Jennifer T. Allen, the site has built a reputation for delivering high-quality content that caters to both beginners and seasoned professionals in the game development community. Allen's extensive background in game design, combined with her commitment to teaching, lends credibility to the tutorials offered on the site. The article itself has received positive reception for its clear, practical guidance on creating realistic water materials in Unreal Engine 4, which is crucial for enhancing the visual quality of game environments. While World of Level Design is generally praised for its thoroughness, some users have noted occasional discrepancies in tutorial details or updates, highlighting the importance of cross-referencing information with official Unreal Engine documentation.

In analyzing the reference "Materials Starter Content: Water Instance" in relation to the current task of creating a single-layer water material in Unreal Engine, several key aspects are highlighted. The reference outlines the process of setting up a water material using Unreal Engine's Material Editor, providing a foundational understanding of the workflow. It discusses the basic properties of water, including techniques for achieving realistic reflections and implementing refraction effects that allow light to bend as it passes through the water, enhancing realism. Additionally, the tutorial includes methods for simulating surface movement, such as waves or ripples, contributing to the dynamic quality of the water. Light interaction techniques are covered, ensuring proper lighting effects on the water surface. The reference emphasizes the importance of performance optimization, ensuring that the water simulation runs smoothly in real-time applications. Furthermore, it discusses various visual tricks and settings that can be adjusted in the Material Editor to enhance the overall appearance of the water while leveraging Unreal Engine's starter content, providing practical context for effectively using existing assets in projects. Overall, this comprehensive guide serves as a valuable resource for developing a convincing water material while balancing visual fidelity and performance.

Reflecting on the "Materials Starter Content: Water Instance" tutorial from World of Level Design, I found the resource to be highly informative and practical. I particularly enjoyed the clear, step-by-step approach that made complex concepts accessible, especially for those new to Unreal Engine. The emphasis on performance optimization is something I wholeheartedly agree with, as it’s crucial for real-time applications. However, I did notice a few areas where additional details could enhance the learning experience, such as more in-depth explanations of the underlying principles behind some techniques. Overall, while the tutorial effectively equips users with the necessary skills to create realistic water materials, I believe it could benefit from further elaboration on certain aspects to cater to a broader range of experience levels.

###### Single Layer Water Material in Horizon Forbidden West

Horizon Forbidden West, developed by Guerrilla Games and published by Sony Interactive Entertainment, is a critically acclaimed action role-playing game released in 2022. As the sequel to Horizon Zero Dawn, it carried high expectations, given the success and reputation of its predecessor. Guerrilla Games, known for its visually stunning and narrative-driven experiences, continued to push technical boundaries in Forbidden West, particularly with its open-world design and next-gen performance. The game received widespread praise for its expansive world, environmental detail, and engaging combat mechanics. However, it faced criticism for its minor technical issues at launch, including performance bugs and glitches that required post-launch patches. Despite these issues, the game maintained a strong reputation within the gaming community, earning multiple nominations for awards such as Best Game Direction and Best Art Direction at prestigious ceremonies like The Game Awards.

In reference to Horizon Forbidden West, several aspects can be analyzed to inform the creation of a single-layer water material in Unreal Engine. The game is renowned for its realistic water rendering, including reflections, refractions, and surface movement, which serve as valuable inspiration for crafting visually convincing water materials. The dynamic surface movement and fluid interactions in the game offer insight into replicating natural wave patterns and water flow in Unreal Engine. Additionally, Horizon Forbidden West excels in how light interacts with water, utilizing advanced techniques for reflections and refractions that can enhance the realism of light-water interaction in this task. Guerrilla Games also managed to deliver high-quality visuals while maintaining optimized performance, providing useful examples of how to balance visual fidelity and system efficiency, such as through shader optimizations. Finally, the game’s seamless integration of water into its broader environment highlights best practices for ensuring the water material blends well with surrounding elements, enhancing the overall immersion.


Overall, I greatly enjoyed Horizon Forbidden West for its stunning visuals, particularly the water rendering, which felt incredibly immersive and lifelike. The attention to detail in how the game simulates natural environments, including the interaction between light and water, is impressive and something I found inspiring for my own work. However, I did notice that the game experienced some technical issues at launch, which affected performance and immersion—an aspect I didn't fully agree with, given the expectations for a AAA title. Despite this, I agree with the majority of the critical acclaim the game received, especially in terms of its artistic direction and technical achievements. The balance between visual fidelity and performance optimization is something I appreciated and will keep in mind as I work on similar tasks in Unreal Engine.

## Implementation

### What was the process of completing the task? What influenced your decision making?

<br>

[Single Layer Water Material Blueprint](https://blueprintue.com/blueprint/tmcq9gan/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/tmcq9gan/" scrolling="no" allowfullscreen></iframe>

*Link 1. A single layer water material*

I created a single-layer water material that allows light to refract, reflect, and remain transparent. Additionally, I incorporated panning normals to simulate the movement of the water surface, creating a realistic ripple effect.

### What creative or technical approaches did you use or try, and how did this contribute to the outcome?

- Did you try any new software or approaches? How did the effect development?

<br>

![onhover image description](https://beforesandafters.com/wp-content/uploads/2021/05/Welcome-to-Unreal-Engine-5-Early-Access-11-16-screenshot.png)
*Figure 2. An example of an image as a figure. This image shows where to package your Unreal project!.*

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

- Did you have any issues completing the task? How did you overcome them?

## Outcome

Here you can put links required for delivery of the task, ensure they are properly labelled appropriately and the links function. The required components can vary between tasks, you can find a definative list in the Assessment Information. Images and code snippets can be embedded and annotated if appropriate.

- [Outcome Video Link](https://www.youtube.com/watch?v=AmShFJviROE)

<iframe width="560" height="315" src="https://www.youtube.com/embed/AmShFJviROE?si=HHEY4uOPivo9yIui" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game/tree/main)

## Critical Reflection

### What did or did not work well and why?

- What did not work well? What parts of the assignment that you felt did not fit the brief or ended up being lacklustre.
- What did you think went very well? Were there any specific aspects you thought were very good?

### What would you do differently next time?

- Are there any new approaches, methodologies or different software that you wish to incorporate if you have another chance?
- Is there another aspect you believe should have been the focus?

## Bibliography

Single Layer Water Shading Model in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/single-layer-water-shading-model-in-unreal-engine 

UE4 Tutorial: How Make Water Material in ‘Starter Content’ Work Without Stretching or Distortions (s.d.) At: https://www.worldofleveldesign.com/categories/ue4/materials-starter-content-water-instance.php

Horizon Forbidden West PS4/PS5 (2022) Developed by Guerrilla Games and published by Sony Interactive Entertainment (SIE)