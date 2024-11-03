# Task: Physics Door

Technical Art

Sidd Ghosalkar

2304613

## Research

For this project, I conducted extensive research on Physics Door and Physics Constraint and explored the Unreal Engine to create a more immersive experience. I prioritized studying official documentations to develop my ability to learn new techniques independently and without direct guidance.

Additionally, I sought insights from practical tutorial to deepen my understanding of Physics Door and Physics Constraint, to ensure its proper implementation within the game.

#### Sources

###### Physics Constraint Component Unreal Engine User Guide

"Physics Constraint Component User Guide" by Epic Games, a leading developer and publisher, offers a comprehensive resource on using the Physics Constraint Component within Unreal Engine. Known for producing high-quality developer tools and Unreal Engine's high regard in the game development industry, Epic Games provides this guide to enhance the understanding of physics constraints for both new and experienced users. Epic Games documentation is widely recognized for its clarity and depth, helping users leverage Unreal Engine's capabilities effectively and is frequently referenced in game development circles for best practices and technical insights.

The reference provides key insights for designing a responsive, physics-driven door. It covers configuring movement limits, damping, and stiffness to control how the door swings and responds to force. It also addresses proper attachment to ensure realistic interaction with the door frame, setting rotation axes for natural movement, and enabling the door to react to player input or other physical objects. These components are essential for creating a door that behaves naturally within Unreal Engine’s physics system.

I found the guide valuable for its structured approach to configuring physics constraints, which was both clear and effective. The emphasis on practical application, particularly for setting movement limits and simulating realistic interactions, felt very useful for creating a responsive door system. However, the documentation occasionally lacked depth in certain areas, such as troubleshooting specific issues that might arise with more complex setups. Overall, I agreed with its approach to constraints and appreciated its usability, though a bit more detail could enhance its effectiveness.

###### Physics Constraint Reference Unreal Engine

"Physics Constraint Reference" from the Unreal Engine documentation, provided by Epic Games, is an authoritative source on implementing physics constraints in Unreal Engine 5.0. Epic Games, known for Unreal Engine's extensive use in gaming and interactive 3D creation, has earned a strong reputation for delivering comprehensive, technically sound resources. This documentation supports developers with clear, accurate guidelines that align with industry standards, making it invaluable for creating realistic physics interactions in games. Unreal's community and widespread acclaim highlight its high credibility and utility.

For creating a physics-driven door in Unreal Engine, the Physics Constraint Reference explores key elements that are essential to your task. These include setting up hinge constraints, adjusting parameters for realistic motion, and using collision detection to interact with player input and objects. The documentation also covers how to manipulate constraint limits, damping, and stiffness to simulate realistic door movements that react naturally within the game world. This guidance is foundational for establishing responsive, physics-based interactions in Unreal Engine environments.

Overall, I found the Physics Constraint Reference very helpful for guiding my work on the physics-driven door. I appreciated its clear explanations on parameters like hinge constraints and damping, which simplified the process of adding realistic physics. However, I would have preferred more practical examples or troubleshooting tips for complex interactions, as this would add context to the technical details. While I agree with most of the information presented, additional examples would strengthen its utility for beginners in physics simulation setups.


###### Physics Door Thejollygrimreaper

"Unreal Engine 5 Physics Constraints: A Door You Can Push" is part of a collection from a seasoned game development content creator on Unreal Engine. Known for accessible, step-by-step explanations, this creator has earned a positive reputation for aiding both beginners and intermediate developers. Their tutorials are appreciated for their practical applications, helping developers navigate UE5's complex tools, such as physics constraints. While this content is not award-winning, it is widely regarded as a useful resource, bolstered by the creator’s clear instruction and attention to detail in Unreal Engine mechanics.

For this task, essential aspects include setting up and configuring a physics-driven door in Unreal Engine using physics constraints. The analysis involves exploring Unreal Engine's physics systems to ensure realistic door movement and interaction with other objects and player inputs. It covers adjusting constraint properties, collision settings, and hinge functionality, all necessary for creating smooth, responsive door mechanics. Testing and fine-tuning the interactions within the environment are also important to achieve a seamless experience, responsive to dynamic in-game actions.

I appreciated the tutorial’s clarity in demonstrating the setup and properties of Unreal Engine's physics constraints, which made configuring the door mechanics straightforward and effective. The hands-on approach helped solidify the process, especially for real-world applications. However, I found some sections could benefit from additional depth, especially on troubleshooting common issues that may arise during implementation. Overall, I agreed with the techniques presented, as they aligned well with best practices for interactive physics objects in Unreal Engine.

## Implementation

### What was the process of completing the task? What influenced your decision making?

I created an actor to set up a physics-based door mechanism. I started by adding two static meshes: one for the door and the other for the door frame, establishing the visual elements. Next, I added box collisions to both the door and door frame, enabling interaction when the player collides with the door. I then configured a physics constraint, setting its Z rotation to -90 to control the door’s rotational axis. I named the constraint component door and adjusted its swing and twist motions—Swing Motion 1 was set to Limited, Swing Motion 2 to Locked, and Twist Motion to Locked. I also set the swing limit to 90 degrees and chose Twist and Swing as the angular drive mode. For the target orientation, I set the Y-axis to 90 degrees and enabled both twist and swing drives. These settings allow the door to open when the player collides with it, then swing back and forth before gradually coming to a stop, creating a realistic, interactive experience.

## Outcome

- [Outcome Video Link](https://www.youtube.com/watch?v=qQ6ekMlRhmA)

<iframe width="560" height="315" src="https://www.youtube.com/embed/qQ6ekMlRhmA?si=RtQp6bkf7GlOcUGV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game/tree/main)

## Critical Reflection

### What did or did not work well and why?

I encountered significant difficulty in locating relevant sources for the task. Despite my efforts to search through various websites and videos, the material I found was either limited in scope or not directly applicable. Consequently, I had to adapt my approach by broadening my search criteria and seeking alternative perspectives, though it remained a time-consuming process. I would have preferred if this task included a programming component. Incorporating programming would have made the project more engaging and allowed me to apply technical skills in a practical context, making the experience more rewarding. Additionally, programming could have introduced new learning opportunities, particularly through problem-solving and coding challenges, which would have deepened my understanding of the topic. Without it, the task feels somewhat limited, and I miss the chance to work directly with code as part of the process.

The implementation of the physics-based door was successful.Each stage progressed smoothly, resulting in a door mechanism that functions as intended within the environment. I was able to accurately incorporate the necessary physics interactions, ensuring that the door responds realistically to player actions and environmental forces. This aspect of the project allowed me to apply and refine my knowledge of physics principles in game development, and I'm pleased with how effectively the door enhances the interactive experience.

### What would you do differently next time?

Another approach to this setup would be to program the door's physics directly, rather than using a physics constraint on the actor. By scripting the door’s movements, I could achieve more control over its interactions, such as fine-tuning its swing speed, dampening effects, and response time based on the player’s actions. This method would allow for customization in how the door responds to forces, enabling specific behaviors like adjusting the swing arc or controlling how quickly the door slows down. Programming the physics would also provide more flexibility for adding unique interactions or conditions, ultimately allowing for a more tailored and precise outcome.

## Bibliography

Physics Constraint Component User Guide in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/physics-constraint-component-user-guide-in-unreal-engine

Physics Constraint Reference in Unreal Engine | Unreal Engine 5.0 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/physics-constraint-reference

How To Tutorial : Unreal Engine 5 Physics Constraints a Door you can push (2023) At: https://www.youtube.com/watch?v=rUCwGMOWZso 

## Declared Assets
ChatGPT (s.d.) At: https://chatgpt.com
