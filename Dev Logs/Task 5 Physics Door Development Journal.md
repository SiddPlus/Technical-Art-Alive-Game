# Task: Physics Door

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

## Declared Assets

