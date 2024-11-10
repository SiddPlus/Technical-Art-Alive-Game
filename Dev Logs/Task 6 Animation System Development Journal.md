# Task: Animation System

Technical Art

Sidd Ghosalkar

2304613

## Research

### What sources or references have you identified as relevant to this task?

For this project, I conducted extensive research on Animation Blueprint, Blend Space and Animation Montages and explored the Unreal Engine to create a more immersive experience. I prioritized studying official documentations to develop my ability to learn new techniques independently and without direct guidance.

#### Sources

###### Animation Blueprint Unreal Engine Documentation

"Animation Blueprints in Unreal Engine," is an official guide provided by Epic Games, the developer of Unreal Engine. Epic Games, widely regarded as an industry leader in game development, is known for its groundbreaking contributions to real-time 3D graphics, virtual production, and interactive content creation. With Unreal Engine, Epic has set a high standard in the gaming industry, consistently driving innovation with advanced tools that support animation, simulation, and physics. The official documentation is highly valued by developers, educators, and enthusiasts, offering authoritative, in-depth guidance for working with Unreal Engine's powerful features. It has received positive feedback from users for its clarity, accessibility, and the practical insights it provides, making it an essential resource for both beginners and experienced developers. While some users have occasionally noted a steep learning curve with Unreal Engine documentation, Epic continually updates its resources, reflecting its commitment to accessibility and usability.

In reference to the current task provides detailed guidance on key aspects necessary for creating a character animation system. The guide covers the setup and utilization of animation blueprints, which are essential for controlling and managing complex character behaviors. It also explores blend spaces, a feature that allows for smooth blending between different animation states, such as walking, running, and idle. Additionally, the documentation explains the implementation of state machines, which help organize transitions between animations like jumping and falling, ensuring seamless movement across various states. By focusing on these components—animation blueprints, blend spaces, and state machines—this source provides foundational knowledge for achieving fluid and responsive character animations. This aligns closely with the task's objectives, making it a valuable resource for creating an efficient and realistic animation system in Unreal Engine.

Overall, I found the documentation to be well-structured and insightful, with clear explanations on essential topics like blend spaces, animation blueprints, and state machines. I appreciated the practical approach Epic Games takes, as the examples and visual aids make it easier to follow complex processes. The guide’s emphasis on creating smooth, responsive animations resonated with me, as it directly supports the goals of my project. However, I found some sections lacking in detailed troubleshooting advice, which could be challenging for those new to Unreal Engine. Despite this, I agree with the guide’s approach to animation system design, as it aligns well with industry standards for character fluidity and responsiveness. Overall, it’s a valuable resource, and I would recommend it to anyone aiming to deepen their understanding of character animation within Unreal Engine.

###### Blend Space Unreal Engine Documentation

The source, Epic Games’ official documentation on Blend Spaces in Unreal Engine, provides a comprehensive guide on implementing Blend Spaces within Unreal Engine 5. As the creator of Unreal Engine, Epic Games is widely recognized for its industry-leading game engine, utilized by professionals and hobbyists alike across gaming, film, and other creative industries. The Unreal Engine’s documentation is regarded as a reliable and authoritative resource, consistently praised for its clarity, depth, and usability. With numerous awards for innovation and industry impact, Epic Games has cultivated a reputation for maintaining high standards of quality and accessibility in its educational materials, making this source an essential reference for developers aiming to leverage Blend Spaces effectively within their projects.

In analyzing the Unreal Engine documentation on Blend Spaces, several key aspects were considered for creating an effective character animation system. This includes understanding how Blend Spaces enable smooth blending between animations based on parameters such as speed or direction, which is critical for seamlessly transitioning between walking, running, and idle states. The guide also highlights setting up and customizing animation blueprints, which are necessary for defining state machines and conditions for transitioning between actions like jumping, falling, and standing idle. Additionally, the documentation covers essential configuration options, parameters, and practical examples that provide foundational knowledge for managing complex animation states. These insights directly support the task's goals, enabling the development of fluid, realistic character movement by integrating multiple animations into a cohesive system.

Overall, I found the Unreal Engine documentation on Blend Spaces both informative and well-structured, making it easy to follow and implement the concepts into my animation system. I appreciated the step-by-step explanations and visual aids, which clarified each aspect of setting up Blend Spaces and creating smooth animation transitions. The source's emphasis on practical application through examples was particularly helpful, aligning well with the goals of my project. However, I felt that certain sections could have benefited from more advanced tips for complex setups or troubleshooting common issues, as this would have enriched the learning experience. Despite this, I fully agree with the recommended approaches and found the resource invaluable for understanding and implementing Blend Spaces effectively within my character animation system.

###### Animation Montages Unreal Engine Documentation

The Unreal Engine documentation on Animation Montages is published by Epic Games, the developer behind Unreal Engine, one of the most influential and widely used game engines in the industry. Epic Games is renowned for its high-quality, professional-grade tools that support advanced graphics, animation, and physics, empowering developers to create complex, immersive gaming experiences. This documentation provides detailed insights into Animation Montages, a powerful feature for managing complex animations within games. Known for thoroughness and accuracy, Epic Games’ official documentation is widely respected and trusted by developers at all levels, from beginners to experts. However, some users occasionally find that certain technical explanations assume a level of prior knowledge, which can pose challenges for newer developers.

In the current task, the analysis focuses on key aspects of creating a character animation system in Unreal Engine using the information from the Animation Montages documentation. These aspects include the integration of animation blueprints to control the flow of animations, the use of blend spaces to seamlessly transition between walking, running, idle, jumping, and falling animations, and the implementation of state machines to manage the different character states. The documentation's focus on Animation Montages will be particularly relevant for organizing and controlling animation sequences, ensuring that transitions between different states, such as idle to run or run to jump, are smooth and fluid. Understanding how to leverage these features in Unreal Engine will be crucial for achieving the desired outcome in the animation system.

I found the Unreal Engine documentation on Animation Montages to be very informative and well-structured, offering a clear and comprehensive guide for integrating complex animations into game development. The detailed explanations on animation blueprints, blend spaces, and state machines were especially helpful, providing a solid foundation for the task at hand. I appreciated the emphasis on practical applications, such as how to use Animation Montages to manage different animation sequences effectively. However, I did find some sections a bit dense, assuming a higher level of familiarity with Unreal Engine’s interface and terminology. While I agree with most of the documentation’s recommendations, I would have preferred more beginner-friendly examples for those less experienced with advanced animation techniques in Unreal Engine. Overall, the source is reliable and beneficial but could be more accessible for newcomers.

## Implementation

### What was the process of completing the task? What influenced your decision making?

I created a blendspace to handle the transition from idle to running animations. Next, I set up an animation blueprint and defined a state for movement within it. Inside this state, I established transitions between the blendspace and the jump animation states. For the transition from blendspace to jump, I set the IsJumping variable to true, and for the transition back from jump to blendspace, I set IsJumping to false. In the blendspace node, I connected the Speed variable to control the blendspace, while in the jump node, I set up the jump animation. In the event graph, I connected both the Speed and IsJumping variables to the player character, ensuring smooth transitions. Finally, I added the default slot after the movement state to complete the setup.

## Outcome


- [Example Video Link](https://www.youtube.com/watch?v=rYyjzmbGlaE)

<iframe width="560" height="315" src="https://www.youtube.com/embed/rYyjzmbGlaE?si=r3oDIcSgJN-xUVnJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game/tree/main)

## Critical Reflection

### What did or did not work well and why?

I found that there was no programming involved in this task, which was somewhat disappointing. I would have preferred if it had included some programming aspects, as it would have made the process more engaging and aligned with my interests.

The process of importing animations and the model, followed by creating the blend space and animation blueprint, went smoothly. Each step came together effectively, resulting in a seamless workflow that helped bring the character animations to life within the project.

### What would you do differently next time?

An alternative approach to using the animation system would have been to program the transitions between animations directly in C++. By handling the animations in code, I would have gained more control over the transition logic and conditions, potentially optimizing performance by bypassing the visual animation system. This approach would involve manually setting up conditions for each transition, such as detecting speed changes or jump inputs, and triggering the appropriate animations through code. Though this method requires more in-depth programming, it allows for highly customized and efficient control over the character's animations.

## Bibliography

Animation Blueprints in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/animation-blueprints-in-unreal-engine

Blend Spaces in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/blend-spaces-in-unreal-engine

Animation Montage in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/animation-montage-in-unreal-engine
