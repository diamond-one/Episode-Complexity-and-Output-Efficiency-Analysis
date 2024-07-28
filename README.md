# Episode Complexity and Output Efficiency Analysis
[Back to Portfolio](https://github.com/diamond-one/Data-Analytics-Portfolio)
## Overview

In this project, I analyzed the complexity and efficiency of the animation production pipeline for episodes of the animated series. The goal was to understand how the complexity of each episode affected production times in the Blocking and Spline phases, and to identify opportunities for optimizing workflows and resource allocation.

## Stories and Solutions

### 1. Quantifying Time Allocation for Complex Episodes

**Challenge:**  
Quantifying an episode's complexity accurately was crucial to ensuring efficient resource allocation and timely production. However, without a standardized method, predicting the necessary time and resources for 'complex' episodes was challenging, often leading to scheduling overruns and increased costs.

**Solution:**  
To tackle this challenge, we developed a "Complexity Calculator" tool. This tool standardizes the assessment of shot complexity by evaluating various contributing factors. It calculates an overall complexity score for each episode by using weighted averages for each specific complexity element. The key factors considered in the complexity assessment included:

- The number of characters in each shot.
- Character interaction.
- Prop handling.
- Gymnastic movements or complex actions.
- Camera framing, categorized as long, medium, or close-up shots.
- Unusual camera moves.
- The introduction of new characters, which typically result in more notes and revisions.
- Dialogue scenes.
- Walking and running sequences.
- Unique locomotion, including quadroped movement.
- Background interaction.
- Complex lighting setups.
- Simulation elements.
- Unique outfits for characters.
- Transition shots and cuts on action.

These factors ensure a detailed and standardized approach to assessing the complexity of episodes, helping in accurate scheduling and resource planning.

![image](https://github.com/user-attachments/assets/a68c9581-5b33-4e07-9d6e-64dfa7bc4aff)


The Complexity Calculator was made accessible to producers, allowing them to use it during the early stages of production. By identifying and potentially reducing complexity early on, production teams could streamline processes and minimize potential delays, leading to more manageable and efficient production schedules.

**Visualization of complexity rating vs time taken to animate, blocking and spline phases** 
![Blocking complexity ](https://github.com/user-attachments/assets/b6b9fde5-1f8f-42c5-b8cc-389150dd2e00)
![Spline complexity ](https://github.com/user-attachments/assets/9603e0c3-4611-4865-b559-610971ba5ba2)


**Outcome:**  
While there was not always a direct correlation between complexity ratings and the actual time taken for the Blocking and Spline phases, the following scaling was established to provide a baseline for expected additional time based on complexity:
- Complexity Rating 5: 0% additional time
- Complexity Rating 6: 10% additional time
- Complexity Rating 7: 20% additional time
- Complexity Rating 8: 30% additional time
- Complexity Rating 9: 40% additional time
- Complexity Rating 10: 50% additional time

  
## Conclusion 
The Complexity Calculator and the established scaling system have proven to be invaluable tools in optimizing the animation production pipeline. By providing a quantitative measure of episode complexity, the tool empowers producers to make data-driven decisions that enhance scheduling accuracy and resource allocation. This proactive approach not only streamlines workflows but also minimizes the risk of costly overruns associated with unexpectedly complex episodes.

A key advantage of the Complexity Calculator is its ability to provide producers with a clear benchmark for episode complexity. This clarity is crucial in negotiations with clients, allowing producers to set realistic expectations and push back when proposed episodes exceed feasible production parameters. Moreover, the tool's detailed breakdown of complexity factors enables producers to pinpoint specific elements that can be adjusted, ensuring that projects stay within scope and budget while maintaining high-quality standards.

Looking ahead, the insights gained from implementing the Complexity Calculator will guide continuous improvements in production efficiency and quality. The tool's methodology will be refined and expanded based on ongoing data analysis and industry feedback, ensuring it remains a critical asset in managing the complexities of animation production.

[Back to Portfolio](https://github.com/diamond-one/Data-Analytics-Portfolio)
