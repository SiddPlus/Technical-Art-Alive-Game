# Task: Linear Interpolation

Technical Art

Sidd Ghosalkar

2304613

## Research

For this project, I conducted extensive research on Linear Interpolation and explored the Unreal Engine to create a more immersive experience. I prioritized studying insights from technical experts to develop my ability to learn new techniques independently and without direct guidance.

Additionally, I sought valuable knowledge from practical tutorials to deepen my understanding of Linear Interpolation and ensure its proper implementation within the game.

#### Sources

Linear Interpolation Matthew Wadstein

The video titled "WTF Is? Material - Linear Interpolate in Unreal Engine 4" from the YouTube channel of Matthew Wadstein, a well-known developer and educator in the game development community, particularly for Unreal Engine 4 (UE4). Wadstein's "WTF Is?" series breaks down complex Unreal Engine concepts into accessible, short tutorials. His work has gained recognition within the game development community due to its practicality and clarity, with the channel serving as a go-to resource for beginners and advanced users alike. While Wadstein's tutorials are widely praised for their educational value, they are considered most useful when supplemented by hands-on practice.

In the video, Matthew Wadstein covers the fundamental aspects of using linear interpolation (lerp) in Unreal Engine. He explains the core concept of lerp, demonstrating how to implement it using the Lerp node within materials. The tutorial shows practical applications such as blending between two values, like colors or positions, over time or based on a parameter. Wadstein also explores controlling interpolation with parameters such as time or user input, and provides visual feedback of the transition results directly within Unreal Engine’s interface.

I found the video very clear and helpful, particularly in its step-by-step explanation of how to implement the Lerp node in Unreal Engine. The examples provided were practical and easy to follow, making the technical content accessible. I appreciated the focus on real-time visual feedback, which solidified my understanding of the concept. However, I would have liked a bit more discussion on advanced applications of lerp beyond basic transitions. Overall, the tutorial was well-executed and effective for both beginners and intermediate developers.

Linear Interpolation Alan Zucconi

The article "Linear Interpolation" is authored by Zucconi, a game developer and educator known for his tutorials on game development and programming. His work is particularly influential within the indie game development community, where he is respected for simplifying complex mathematical and programming concepts. Zucconi’s tutorials are well-received for their clarity, and he has contributed to several popular games, including Pikuniku and Still Time. His website has become a go-to resource for developers, praised for its in-depth coverage of technical topics such as shaders and AI.

Alan Zucconi’s article on linear interpolation (lerp) delves into the mathematical principles behind lerp, a critical technique in game development for smoothly transitioning between values. It explores applications such as color blending, position adjustments, and texture transitions, explaining the lerp formula and providing practical coding examples. Zucconi also offers visual demonstrations to clarify how lerp enables smooth transitions. This analysis is especially relevant for tasks involving Unreal Engine, where lerp is commonly implemented in material nodes to blend values dynamically over time.

I found Zucconi’s article on linear interpolation both insightful and well-structured. I particularly appreciated his clear explanations and visual demonstrations, which made complex concepts accessible. I agree with his emphasis on lerp’s versatility in game development, as it is indeed fundamental for creating smooth transitions. However, I felt that some technical details could have been explored further, particularly regarding performance considerations in real-time applications. Overall, it’s a valuable resource for anyone looking to deepen their understanding of lerp in game design. 

Linear Interpolation David L. Johnson

The article "Linear Interpolation Explained" authored by David L. Johnson and published on GameDev.net, serves as a valuable resource for game developers seeking to understand the concept of linear interpolation (lerp) in programming. GameDev.net, a respected online community and knowledge base for game developers, boasts a reputation for providing high-quality tutorials and insights into game design and development. Johnson, known for his expertise in gameplay programming, presents the topic in a clear and accessible manner, making it suitable for both novice and experienced developers. The article has received positive feedback for its straightforward explanations and practical examples, enhancing its credibility in the gaming community. While the article has not garnered specific awards, its influence is evident in the way it demystifies a fundamental concept crucial for game mechanics, highlighting the importance of lerp in creating smooth animations and transitions.

In analyzing the current task focused on linear interpolation (lerp) in game development, several key aspects emerge. First, it is essential to define and explain what linear interpolation is, including the mathematical principles behind it. Understanding its applications in game development is crucial, as lerp is widely used for smoothly transitioning between values such as colors, positions, and textures. The implementation of the Lerp node in Unreal Engine will be explored, providing step-by-step instructions and best practices for its use in materials. Performance considerations will also be addressed, discussing the efficiency of using lerp in real-time applications and its impact on overall game performance. Practical examples illustrating lerp in action will demonstrate how it enhances gameplay and user experience. Additionally, the analysis will cover how lerp can be controlled by parameters, allowing for dynamic value changes over time or in response to user input. A visual representation of lerp's effects in a game environment will be provided, alongside common issues and troubleshooting tips. Finally, a brief comparison with other interpolation methods, such as cubic or spline interpolation, will highlight lerp's unique advantages and limitations, while community feedback and resources will be reviewed to offer further learning opportunities.

In concluding my exploration of David L. Johnson's article "Linear Interpolation Explained," I found the clear and accessible explanations particularly enjoyable, making complex concepts easier to grasp. The practical examples provided were especially helpful, as they illustrated the real-world applications of lerp in game development, which I fully agree enhances the reader's understanding. However, I would have appreciated a more in-depth discussion on potential pitfalls when implementing lerp, as awareness of common issues could further empower developers. Overall, I agree with the article's emphasis on the significance of lerp in creating smooth transitions and its impact on user experience, and I believe it serves as a solid foundation for anyone looking to implement this fundamental technique in their projects.

## Linear Interpolation Research

### Explanation of the Lerp Function

The Lerp (linear interpolation) function is a mathematical formula used to create smooth transitions between values.

$$ 
Lerp(a, b, t) = a + t(b − a)
$$

a: Starting value (the value at t = 0)
b: Ending value (the value at t = 1)
t: Interpolation factor, typically a value between 0 and 1.

### Examaple

a is red and b is blue:

t =  0, the color will be red.

t = 0.25, the color will be reddish-purple shade.

t = 0.5, the color  will be purple.

t = 0.75, the color will be bluish-purple shade.

t = 1, the color will be blue

### Real-World Examples

- Blending Textures: When creating smooth transitions between two textures, Lerp can be used to blend their colors or patterns. For instance, blending a grassy texture into a rocky texture based on player movement or environmental changes.

- Moving Objects: Lerp is often applied to interpolate the position of objects over time. For example, moving a character smoothly from one point to another in a scene. By incrementally adjusting the character's position based on the value of t, the movement appears fluid and natural.

- Creating Smooth Animations: Lerp is frequently used to create smooth animations in character movements, camera transitions, and UI elements. For example, easing the camera from one position to another during a cutscene can create a more cinematic experience.

- Color Gradients: Developers often use Lerp to create color gradients in user interfaces or environmental lighting. For instance, changing the sky color from day to night by interpolating between different colors based on the time of day.

## Implementation

### What was the process of completing the task? What influenced your decision making?

- What was the process of completing the task at hand? Did you do any initial planning?
- Did you receive any feedback from users, peers or lecturers? How did you react to it?

<br>

[Color Lerping Material Blueprint](https://blueprintue.com/blueprint/gmdicac1/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/gmdicac1/" scrolling="no" allowfullscreen></iframe>

*Link 1. A material lerping between 2 colors*

[Texture Lerping Material Blueprint](https://blueprintue.com/blueprint/4hjjq1ls/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/4hjjq1ls/" scrolling="no" allowfullscreen></iframe>

*Link 2. A material lerping between 2 textures*

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

- Did you have any issues completing the task? How did you overcome them?

## Outcome

- [Outcome Video Link](https://www.youtube.com/watch?v=stEsIGXVEMs)

<iframe width="560" height="315" src="https://www.youtube.com/embed/stEsIGXVEMs?si=3LR6vz71N89Jg6UG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game)

## Critical Reflection

### What did or did not work well and why?

- What did not work well? What parts of the assignment that you felt did not fit the brief or ended up being lacklustre.
- What did you think went very well? Were there any specific aspects you thought were very good?

### What would you do differently next time?

- Are there any new approaches, methodologies or different software that you wish to incorporate if you have another chance?
- Is there another aspect you believe should have been the focus?

## Bibliography

WTF Is? Material - Linear Interpolate in Unreal Engine 4 (2016) At: https://www.youtube.com/watch?v=fckeT6GyvPc 

Zucconi, A. (2021) Linear Interpolation. At: https://www.alanzucconi.com/2021/01/24/linear-interpolation/ 

Linear Interpolation Explained (s.d.) At: https://gamedev.net/tutorials/programming/general-and-gameplay-programming/linear-interpolation-explained-r5892 


