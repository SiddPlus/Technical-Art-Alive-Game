# Task: Anti-Aliasing

Technical Art

Sidd Ghosalkar

2304613

## Research

```Markdown

As I have done research regarding Anti-Aliasing for this project in previous formative assignments. I looked into Unreal engine that will help create a more immersive experience. I wanted to focus on official documentation to improve my ability to learn new techniques without explicit instructions.

I also wanted a creative source to help demostrate Anti-Aliasing and learn how it should function within the game.
```
#### Sources

- An opening paragraph about the source stating the author, developer or organisation, this paragraph should explain the source's influence, credentials, critical reception, awards, reputation or any issues with the source. For example, if the source is not reputable. If the source is a game, the issues that occurred during development or if had a poor launch.
- List the aspects analysed in reference to the current task.

```Markdown
Anti-Aliasing Unreal Engine Documentation

"Anti-Aliasing and Upscaling in Unreal Engine" is part of the official Unreal Engine documentation provided by Epic Games, a leader in game development technology. Epic Games, known for creating the Unreal Engine, is renowned for its robust tools used in game design, film production, and interactive experiences. The Unreal Engine has received critical acclaim for its high-fidelity graphics and user-friendly interface, making it a standard in the industry. The documentation is offers in-depth technical guidance and insights to developers of all levels. 

(The different anti-aliasing techniques like Temporal Anti-Aliasing (TAA), Fast Approximate Anti-Aliasing (FXAA), and Multisample Anti-Aliasing (MSAA). These techniques are assessed based on their effects on visual quality, particularly the reduction of jagged edges, and their impact on performance. The documentation also addresses upscaling techniques that improve image sharpness while balancing rendering performance.)

(An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.
Example: I found their implementation and choice great for the context of their narrative and game mechanics. However, for the sequences featured in the assignment, it is more “cinematic” allowing for a different approach for the mix and can be “exaggerated” to drive its narrative function.)


Anti-Aliasing SpringerLink

"Delving Deeper into Anti-Aliasing in ConvNets" is a scientific article published in the International Journal of Computer Vision, a peer-reviewed journal known for its influential work in the fields of computer vision and image processing. The article is authored by prominent researchers, which lends it credibility in the academic community. The journal itself has a strong reputation for high-quality publications, often cited in major studies and technical advancements. However, like all academic work, the article may face scrutiny in terms of reproducibility.

(The various anti-aliasing techniques, such as MSAA, FXAA, and TAA, they effects on visual quality in a real-time scene. The focus will be on how well each method reduces jagged edges and visual artifacts. Additionally, you will assess the trade-offs between visual quality and system performance, considering factors like rendering speed, frame rates, and GPU usage. Finally, the ability of each technique to handle complex real-time scenes will be evaluated to find an optimal balance between performance and image quality.)

(An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.
Example: I found their implementation and choice great for the context of their narrative and game mechanics. However, for the sequences featured in the assignment, it is more “cinematic” allowing for a different approach for the mix and can be “exaggerated” to drive its narrative function.)


Anti-Aliasing Digital Foundry

The video titled "Anti-Aliasing - What Is It And Why Do We Need It?" is produced by Digital Foundry, a popular YouTube channel dedicated to explaining complex technology topics in simple terms. The channel has gained a reputation for its clear, concise explanations and has been well-received by both tech enthusiasts and beginners alike. The video explores anti-aliasing, a technique in digital graphics, and has garnered attention for its accessible approach. Digital Foundry is known for credible content in tech education, though some advanced users may find the material overly simplified.

(The video explores anti-aliasing, a technique that reduces jagged edges in rendered images. It explains various anti-aliasing methods, such as MSAA (Multi-Sample Anti-Aliasing), FXAA (Fast Approximate Anti-Aliasing), and TAA (Temporal Anti-Aliasing). These techniques balance visual quality with performance, improving image clarity while managing hardware resource usage. The video emphasizes the trade-offs between sharper visuals and the computational cost required for each method.)

(An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.
Example: I found their implementation and choice great for the context of their narrative and game mechanics. However, for the sequences featured in the assignment, it is more “cinematic” allowing for a different approach for the mix and can be “exaggerated” to drive its narrative function.)
```

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

Anti Aliasing and Upscaling in Unreal Engine | Unreal Engine 5.4 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/anti-aliasing-and-upscaling-in-unreal-engine

Zou, X., Xiao, F., Yu, Z., Li, Y. and Lee, Y. J. (2023) 'Delving Deeper into Anti-Aliasing in ConvNets' In: International Journal of Computer Vision 131 (1) pp.67–81.

Digital Foundry: Anti-Aliasing - What Is It And Why Do We Need It? (2018) At: https://www.youtube.com/watch?v=NbrA4Nxd8Vo

## Declared Assets

- Please use the [harvard referencing convention](https://mylibrary.uca.ac.uk/referencing).

Infinity Blade: Adversaries in Epic Content - UE Marketplace (s.d.) At: https://www.unrealengine.com/marketplace/en-US/product/infinity-blade-enemies (Accessed  09/09/2024).

---

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
