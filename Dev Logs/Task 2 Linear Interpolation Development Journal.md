# Task: Linear Interpolation

Technical Art

Sidd Ghosalkar

2304613

## Research

### What sources or references have you identified as relevant to this task?

- What type of sources did you identity and want to explore? How would you justify it in reference to the brief set? Think about the focus of the brief.
- What type of sources do you want to avoid? How could these kinds of sources be detrimental to the user experience, immersion or implementation?

#### Sources

- An opening paragraph about the source stating the author, developer or organisation, this paragraph should explain the source's influence, credentials, critical reception, awards, reputation or any issues with the source. For example, if the source is not reputable. If the source is a game, the issues that occurred during development or if had a poor launch.
- List the aspects analysed in reference to the current task.
- An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.

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

![test](../Dev%20Logs/Resources/OIP.jpg)

## Implementation

### What was the process of completing the task? What influenced your decision making?

- What was the process of completing the task at hand? Did you do any initial planning?
- Did you receive any feedback from users, peers or lecturers? How did you react to it?

<br>

```csharp
using UnityEngine;
public class HelloWorld : MonoBehaviour 
{
    public void Start() 
    {
        Debug.Log("Hello World!");
    }
}
```
*Figure 1. An example of using a script as a figure. This script has a `Start()` method!*

### What creative or technical approaches did you use or try, and how did this contribute to the outcome?

- Did you try any new software or approaches? How did the effect development?

<br>

![onhover image description](https://beforesandafters.com/wp-content/uploads/2021/05/Welcome-to-Unreal-Engine-5-Early-Access-11-16-screenshot.png)
*Figure 2. An example of an image as a figure. This image shows where to package your Unreal project!.*

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

- Did you have any issues completing the task? How did you overcome them?

## Outcome

Here you can put links required for delivery of the task, ensure they are properly labelled appropriately and the links function. The required components can vary between tasks, you can find a definative list in the Assessment Information. Images and code snippets can be embedded and annotated if appropriate.

- [Example Video Link](https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstley)
- [Example Repo Link](https://github.com/githubtraining/hellogitworld)
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

- Please use the [harvard referencing convention](https://mylibrary.uca.ac.uk/referencing).

Video game development (2024) In: Wikipedia. At: https://en.wikipedia.org/w/index.php?title=Video_game_development&oldid=1240603537 (Accessed  03/09/2024).

## Declared Assets

- Please use the [harvard referencing convention](https://mylibrary.uca.ac.uk/referencing).

Infinity Blade: Adversaries in Epic Content - UE Marketplace (s.d.) At: https://www.unrealengine.com/marketplace/en-US/product/infinity-blade-enemies (Accessed  09/09/2024).

