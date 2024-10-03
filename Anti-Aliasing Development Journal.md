# Task: Anti-Aliasing

Technical Art

Sidd Ghosalkar

2304613

## Research

```Markdown

As I have done research regarding Anti-Aliasing for this project. I looked into Unreal engine that will help create a more immersive experience. I wanted to focus on official documentation to improve my ability to learn new techniques without explicit instructions.

I also wanted a tech expert sources to help demostrate Anti-Aliasing and learn how it should function within the game.
```
#### Sources

- An opening paragraph about the source stating the author, developer or organisation, this paragraph should explain the source's influence, credentials, critical reception, awards, reputation or any issues with the source. For example, if the source is not reputable. If the source is a game, the issues that occurred during development or if had a poor launch.
- List the aspects analysed in reference to the current task.

```Markdown
Anti-Aliasing Unreal Engine Documentation

"Anti-Aliasing and Upscaling in Unreal Engine" is part of the official Unreal Engine documentation provided by Epic Games, a leader in game development technology. Epic Games, known for creating the Unreal Engine, is renowned for its robust tools used in game design, film production, and interactive experiences. The Unreal Engine has received critical acclaim for its high-fidelity graphics and user-friendly interface, making it a standard in the industry. The documentation is offers in-depth technical guidance and insights to developers of all levels. 

(The different anti-aliasing techniques like Temporal Anti-Aliasing (TAA), Fast Approximate Anti-Aliasing (FXAA), and Multisample Anti-Aliasing (MSAA). These techniques are assessed based on their effects on visual quality, particularly the reduction of jagged edges, and their impact on performance. The documentation also addresses upscaling techniques that improve image sharpness while balancing rendering performance.)

(An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.
Example 1: I found the Unreal documentation clear and easy to navigate, however it was much harder to find specific nodes unless you are familiar with the naming conventions used by Unreal, such as “World Location” and the API documentation is separated from the property references. The Wwise documentation on the other hand is much easier to navigate as they have core topics such as “Using Sounds and Motion to Enhance Gameplay” and examples of how they can be applied, which the unreal documentation lacked. 
Example 2: I found their implementation and choice great for the context of their narrative and game mechanics. However, for the sequences featured in the assignment, it is more “cinematic” allowing for a different approach for the mix and can be “exaggerated” to drive its narrative function.)


Anti-Aliasing SpringerLink

"Delving Deeper into Anti-Aliasing in ConvNets" is a scientific article published in the International Journal of Computer Vision, a peer-reviewed journal known for its influential work in the fields of computer vision and image processing. The article is authored by prominent researchers, which lends it credibility in the academic community. The journal itself has a strong reputation for high-quality publications, often cited in major studies and technical advancements. However, like all academic work, the article may face scrutiny in terms of reproducibility.

(The various anti-aliasing techniques, such as MSAA, FXAA, and TAA, they effects on visual quality in a real-time scene. The focus will be on how well each method reduces jagged edges and visual artifacts. Additionally, you will assess the trade-offs between visual quality and system performance, considering factors like rendering speed, frame rates, and GPU usage. Finally, the ability of each technique to handle complex real-time scenes will be evaluated to find an optimal balance between performance and image quality.)

(An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.
Example 1: I found the Unreal documentation clear and easy to navigate, however it was much harder to find specific nodes unless you are familiar with the naming conventions used by Unreal, such as “World Location” and the API documentation is separated from the property references. The Wwise documentation on the other hand is much easier to navigate as they have core topics such as “Using Sounds and Motion to Enhance Gameplay” and examples of how they can be applied, which the unreal documentation lacked. 
Example 2: I found their implementation and choice great for the context of their narrative and game mechanics. However, for the sequences featured in the assignment, it is more “cinematic” allowing for a different approach for the mix and can be “exaggerated” to drive its narrative function.)


Anti-Aliasing Digital Foundry

The video titled "Anti-Aliasing - What Is It And Why Do We Need It?" is produced by Digital Foundry, a popular YouTube channel dedicated to explaining complex technology topics in simple terms. The channel has gained a reputation for its clear, concise explanations and has been well-received by both tech enthusiasts and beginners alike. The video explores anti-aliasing, a technique in digital graphics, and has garnered attention for its accessible approach. Digital Foundry is known for credible content in tech education, though some advanced users may find the material overly simplified.

(The video explores anti-aliasing, a technique that reduces jagged edges in rendered images. It explains various anti-aliasing methods, such as MSAA (Multi-Sample Anti-Aliasing), FXAA (Fast Approximate Anti-Aliasing), and TAA (Temporal Anti-Aliasing). These techniques balance visual quality with performance, improving image clarity while managing hardware resource usage. The video emphasizes the trade-offs between sharper visuals and the computational cost required for each method.)

(An ending paragraph stating what you enjoyed or disliked, what you agreed with or not agree with.
Example 1: I found the Unreal documentation clear and easy to navigate, however it was much harder to find specific nodes unless you are familiar with the naming conventions used by Unreal, such as “World Location” and the API documentation is separated from the property references. The Wwise documentation on the other hand is much easier to navigate as they have core topics such as “Using Sounds and Motion to Enhance Gameplay” and examples of how they can be applied, which the unreal documentation lacked. 
Example 2: I found their implementation and choice great for the context of their narrative and game mechanics. However, for the sequences featured in the assignment, it is more “cinematic” allowing for a different approach for the mix and can be “exaggerated” to drive its narrative function.)
```
## Anti-Aliasing Techniques Research

### Temporal Super Resolution (TSR)

```Markdown
Overview: TSR is a newer anti-aliasing method designed to upscale lower-resolution images while maintaining clarity and reducing jagged edges. It's particularly effective in real-time rendering environments, like video games, where performance and image quality are essential.
```

Pros:
- Excellent for maintaining high performance with high-quality visuals.
- Preserves more detail and provides a smoother result by blending samples from previous frames.
- Can provide a level of detail and sharpness that rivals higher native resolutions.

Cons:
- May introduce temporal artifacts, such as ghosting or flickering, especially when motion is involved.
- More complex to implement than traditional anti-aliasing techniques.

### Multisample Anti-Aliasing (MSAA)

```Markdown
Overview: MSAA is one of the most popular anti-aliasing techniques. It works by sampling multiple points within each pixel to determine the final color, providing a balance between quality and performance. MSAA is mostly used in 3D rendering environments.
```

Pros:
- Produces high-quality anti-aliasing with relatively moderate performance costs.
- Reduces aliasing at polygon edges effectively without affecting the entire image.
- Better performance than super-sampling anti-aliasing (SSAA).

Cons:
- Doesn't handle transparency or shader aliasing well.
- More computationally expensive than post-processing techniques like FXAA.
- Limited to geometric edges (does not work well on textures or shader aliasing).

### Temporal Anti-Aliasing (TAA)

```Markdown
Overview: TAA is a more modern anti-aliasing method that reduces aliasing by averaging pixels over multiple frames, using motion vectors to track movement and maintain smoothness.
```
Pros:
- Very effective at reducing flickering and shimmering, especially in motion.
- Improves the appearance of detailed textures and softens hard edges effectively.
- Produces visually smooth results with relatively low performance costs.

Cons:
- Prone to artifacts like ghosting, especially in fast-moving scenes.
- Can result in blurring of details, leading to a loss of sharpness compared to other methods.
- Requires proper implementation to reduce artifacts.

### Fast Approximate Anti-Aliasing (FXAA)

```Markdown
Overview: FXAA is a post-processing anti-aliasing method that works by smoothing out edges in the final image after rendering. It is widely used due to its simplicity and low performance impact.
```
Pros:
- Extremely fast, with minimal impact on performance.
- Works on the entire image, not just geometric edges, so it also reduces aliasing on textures and shaders.
- Easy to implement and widely supported.

Cons:
- Lower visual quality compared to MSAA or TAA; tends to blur the image, losing fine details.
- Not effective at reducing aliasing on thin lines or small features.
- Can introduce excessive blurring if not tuned properly.

### Comparison of Techniques

| Technique | Performance Impact | Visual Quality | Handling of Motion Artifact | Handling Transparency/Shader Aliasing | 
| --------  | --------        | --------          | --------                    | --------                              |
| **TSR**   | Moderate        | Very high         | Some ghosting possible      | Good                                  | 
| **MSAA**  | Moderate        | High              | None                        | Poor                                  |
| **TAA**   | Low to moderate | High              | Possible ghosting or blur   | Good                                  |
| **FXAA**  | Low             | Moderate          | None                        | Good                                  |

### Conclusion

```Markdown
In conclusion, TSR is the optimal choice for high-quality rendering with balanced performance, although it may introduce artifacts in motion-heavy scenes. MSAA excels at handling geometric edges, but it struggles with transparency and shader aliasing. TAA offers a solid balance between performance and quality, particularly in scenes with a lot of movement, though it may cause some blurring of fine details. FXAA is best suited for scenarios where performance is critical, but this comes at the expense of image sharpness and overall detail.
```

## Implementation

### What was the process of completing the task? What influenced your decision making?

- What was the process of completing the task at hand? Did you do any initial planning?
- Did you receive any feedback from users, peers or lecturers? How did you react to it?

<br>

[SpinningCube Blueprint] (https://blueprintue.com/blueprint/s7-06ez-/)

[ObjectManager Blueprint] (https://blueprintue.com/blueprint/-n7cvcms/)

*(Figure 1. An example of using a script as a figure. This script has a `Start()` method!)*

### What creative or technical approaches did you use or try, and how did this contribute to the outcome?

- Did you try any new software or approaches? How did the effect development?

<br>

![onhover image description](https://beforesandafters.com/wp-content/uploads/2021/05/Welcome-to-Unreal-Engine-5-Early-Access-11-16-screenshot.png)
*Figure 2. An example of an image as a figure. This image shows where to package your Unreal project!.*

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

- Did you have any issues completing the task? How did you overcome them?

## Outcome

Here you can put links required for delivery of the task, ensure they are properly labelled appropriately and the links function. The required components can vary between tasks, you can find a definative list in the Assessment Information. Images and code snippets can be embedded and annotated if appropriate.

- [Outcome Video Link](https://youtu.be/G4ZIajlx7_8)
- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game)
- [Example Build Link](https://samperson.itch.io/desktop-goose)

<iframe width="560" height="315" src="https://youtu.be/G4ZIajlx7_8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

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
