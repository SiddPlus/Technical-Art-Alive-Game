# Task: Anti-Aliasing

Technical Art

Sidd Ghosalkar

2304613

## Research

For this project, I conducted extensive research on Anti-Aliasing and explored the Unreal Engine to create a more immersive experience. I prioritized studying official documentation to develop my ability to learn new techniques independently and without direct guidance.

Additionally, I sought insights from technical experts to deepen my understanding of Anti-Aliasing and ensure its proper implementation within the game.

#### Sources

###### Anti-Aliasing Unreal Engine Documentation

"Anti-Aliasing and Upscaling in Unreal Engine" is part of the official Unreal Engine documentation provided by Epic Games, a leader in game development technology. Epic Games, known for creating the Unreal Engine, is renowned for its robust tools used in game design, film production, and interactive experiences. The Unreal Engine has received critical acclaim for its high-fidelity graphics and user-friendly interface, making it a standard in the industry. The documentation offers in-depth technical guidance and insights to developers of all levels. 

The different anti-aliasing techniques like Temporal Anti-Aliasing (TAA), Fast Approximate Anti-Aliasing (FXAA), and Multisample Anti-Aliasing (MSAA). These techniques are assessed based on their effects on visual quality, particularly the reduction of jagged edges, and their impact on performance. The documentation also addresses upscaling techniques that improve image sharpness while balancing rendering performance.

In conclusion, I found the discussion on anti-aliasing and upscaling techniques in Unreal Engine to be insightful, particularly in how various methods, such as Temporal Anti-Aliasing (TAA) and DLSS, enhance visual fidelity. The emphasis on achieving a balance between performance and visual fidelity was well articulated. However, I believe a more in-depth exploration of how different hardware configurations impact these techniques would have enhanced the discussion. Overall, it offers valuable insight for optimizing game visuals while maintaining performance efficiency.


###### Anti-Aliasing SpringerLink

"Delving Deeper into Anti-Aliasing in ConvNets" is a scientific article published in the International Journal of Computer Vision, a peer-reviewed journal known for its influential work in the fields of computer vision and image processing. The article is authored by prominent researchers, which lends it credibility in the academic community. The journal itself has a strong reputation for high-quality publications, often cited in major studies and technical advancements. However, like all academic work, the article may face scrutiny in terms of reproducibility.

The various anti-aliasing techniques, such as MSAA, FXAA, and TAA, they effects on visual quality in a real-time scene. The focus will be on how well each method reduces jagged edges and visual artifacts. Additionally, you will assess the trade-offs between visual quality and system performance, considering factors like rendering speed, frame rates, and GPU usage. Finally, the ability of each technique to handle complex real-time scenes will be evaluated to find an optimal balance between performance and image quality.

I found the article insightful, particularly in its exploration of advanced anti-aliasing techniques for convolutional neural networks. The thorough examination of current methods and the suggested improvements were particularly commendable. However, I felt that certain aspects, especially practical applications, could have been explored in greater detail. While I agree with the need for refined methods in image analysis, I believe more emphasis on real-world implementation would have strengthened the overall argument. Overall, the article provided valuable insights into a critical aspect of computer vision.


###### Anti-Aliasing Digital Foundry

The video titled "Anti-Aliasing - What Is It And Why Do We Need It?" is produced by Digital Foundry, a popular YouTube channel dedicated to explaining complex technology topics in simple terms. The channel has gained a reputation for its clear, concise explanations and has been well-received by both tech enthusiasts and beginners alike. The video explores anti-aliasing, a technique in digital graphics, and has garnered attention for its accessible approach. Digital Foundry is known for credible content in tech education, though some advanced users may find the material overly simplified.

The video explores anti-aliasing, a technique that reduces jagged edges in rendered images. It explains various anti-aliasing methods, such as MSAA (Multi-Sample Anti-Aliasing), FXAA (Fast Approximate Anti-Aliasing), and TAA (Temporal Anti-Aliasing). These techniques balance visual quality with performance, improving image clarity while managing hardware resource usage. The video emphasizes the trade-offs between sharper visuals and the computational cost required for each method.

In reflecting on the video about anti-aliasing, I appreciated the clear explanations and visuals that effectively illustrated complex concepts. The breakdown of different techniques was particularly helpful for understanding their applications in graphics. However, I did feel that the technical language could be daunting for beginners. While I fully agree on the significance of anti-aliasing for improving visual quality, I believe a more straightforward introduction would have made the content more approachable for a wider audience.

## Anti-Aliasing Techniques Research

### Temporal Super Resolution (TSR)

Overview: TSR is a newer anti-aliasing method designed to upscale lower-resolution images while maintaining clarity and reducing jagged edges. It's particularly effective in real-time rendering environments, like video games, where performance and image quality are essential.

Pros:
- Excellent for maintaining high performance with high-quality visuals.
- Preserves more detail and provides a smoother result by blending samples from previous frames.
- Can provide a level of detail and sharpness that rivals higher native resolutions.

Cons:
- May introduce temporal artifacts, such as ghosting or flickering, especially when motion is involved.
- More complex to implement than traditional anti-aliasing techniques.

### Multisample Anti-Aliasing (MSAA)

Overview: MSAA is one of the most popular anti-aliasing techniques. It works by sampling multiple points within each pixel to determine the final color, providing a balance between quality and performance. MSAA is mostly used in 3D rendering environments.

Pros:
- Produces high-quality anti-aliasing with relatively moderate performance costs.
- Reduces aliasing at polygon edges effectively without affecting the entire image.
- Better performance than super-sampling anti-aliasing (SSAA).

Cons:
- Doesn't handle transparency or shader aliasing well.
- More computationally expensive than post-processing techniques like FXAA.
- Limited to geometric edges (does not work well on textures or shader aliasing).

### Temporal Anti-Aliasing (TAA)

Overview: TAA is a more modern anti-aliasing method that reduces aliasing by averaging pixels over multiple frames, using motion vectors to track movement and maintain smoothness.

Pros:
- Very effective at reducing flickering and shimmering, especially in motion.
- Improves the appearance of detailed textures and softens hard edges effectively.
- Produces visually smooth results with relatively low performance costs.

Cons:
- Prone to artifacts like ghosting, especially in fast-moving scenes.
- Can result in blurring of details, leading to a loss of sharpness compared to other methods.
- Requires proper implementation to reduce artifacts.

### Fast Approximate Anti-Aliasing (FXAA)

Overview: FXAA is a post-processing anti-aliasing method that works by smoothing out edges in the final image after rendering. It is widely used due to its simplicity and low performance impact.

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

In conclusion, TSR is the optimal choice for high-quality rendering with balanced performance, although it may introduce artifacts in motion-heavy scenes. MSAA excels at handling geometric edges, but it struggles with transparency and shader aliasing. TAA offers a solid balance between performance and quality, particularly in scenes with a lot of movement, though it may cause some blurring of fine details. FXAA is best suited for scenarios where performance is critical, but this comes at the expense of image sharpness and overall detail.

## Implementation

### What was the process of completing the task? What influenced your decision making?

<br>

[SpinningCube Blueprint](https://blueprintue.com/blueprint/s7-06ez-/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/s7-06ez-/" scrolling="no" allowfullscreen></iframe>

*(Link 1's code allows an object spin)*

[ObjectManager Blueprint](https://blueprintue.com/blueprint/-n7cvcms/)

<iframe width="1000" height="500" src="https://blueprintue.com/render/-n7cvcms/" scrolling="no" allowfullscreen></iframe>

*(Link 2's code allows an object to be spawned in a random point contantly then deletes itself after couple of seconds)*

I experimented with four different anti-aliasing methods while spawning spinning objects in Unreal Engine to assess their impact on both visual quality and system performance. By implementing these techniques, I aimed to gauge how each method handled object edges and minimized visual artifacts, like jagged lines, in a dynamic environment with continuous motion. This setup provided a robust testing ground for evaluating anti-aliasing under real-time rendering conditions, ensuring that I could analyze both static and animated scenarios effectively.

To measure performance, I recorded the FPS (frames per second) count and GPU stress for each method, allowing me to pinpoint how each anti-aliasing technique affected system load. The FPS count provided insight into the smoothness of the gameplay experience, while monitoring GPU usage helped determine the computational demands associated with each method. Through these metrics, I could compare how resource-intensive each anti-aliasing technique was, giving me a clearer picture of its overall performance impact.

Analyzing the data, I was able to identify the anti-aliasing method that offered the best balance between visual quality and performance. Some techniques provided excellent edge smoothing but placed a heavier load on the GPU, while others maintained higher FPS but at the cost of reduced image clarity. By comparing the results, I determined which method minimized artifacts without sacrificing too much performance, offering the ideal compromise for my project’s visual and technical needs.

### What creative or technical approaches did you use or try, and how did this contribute to the outcome?

I used Markdown for the first time to write this development log. Overall, writing in Markdown went well; however, I initially struggled with embedding videos and images, as well as HTML, which slowed down the documentation process. On the other hand, I also used Zotero for the first time to manage my references. Utilizing Zotero significantly streamlined the referencing process, making it quicker and more efficient.
<br>

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

I encountered difficulties embedding videos, images, and HTML in Markdown while working on this dev log. To resolve these issues, I turned to Google for solutions and also sought assistance from my lecturer.

## Outcome

- [Outcome Video Link](https://youtu.be/G4ZIajlx7_8)

<iframe width="560" height="315" src="https://www.youtube.com/embed/G4ZIajlx7_8?si=4SG623AUDRrF7nIB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- [Outcome Repo Link](https://github.com/SiddPlus/Technical-Art-Alive-Game)

## Critical Reflection

### What did or did not work well and why?

Getting used to Markdown initially presented a challenge for me. As I spent more time working with it, I gradually became more comfortable navigating its syntax and features. While I appreciate the brief simplicity, I found that it lacks sufficient programming elements to fully satisfy my desire for more programming involvement. I would prefer the brief to offer a deeper level of programming capabilities.

On the research front, I was pleased with the progress I made. The implementation of Anti-Aliasing, in particular, turned out very well. By carefully following the brief, I was able to enhance the visual quality of my project significantly. As I could see a marked improvement in the smoothness of edges and overall graphics quality.

### What would you do differently next time?

I would like to use the computer's performance profiling tools to provide insights into performance bottlenecks and graphical issues.

## Bibliography

Anti Aliasing and Upscaling in Unreal Engine | Unreal Engine 5.4 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/anti-aliasing-and-upscaling-in-unreal-engine

Zou, X., Xiao, F., Yu, Z., Li, Y. and Lee, Y. J. (2023) 'Delving Deeper into Anti-Aliasing in ConvNets' In: International Journal of Computer Vision 131 (1) pp.67–81.

Digital Foundry: Anti-Aliasing - What Is It And Why Do We Need It? (2018) At: https://www.youtube.com/watch?v=NbrA4Nxd8Vo

## Declared Assets

ChatGPT (s.d.) At: https://chatgpt.com