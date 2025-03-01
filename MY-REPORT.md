![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# EtsyBot

This bot..

<!-- WHEN APPLICABLE, REMOVE THE COMMENT MARK AND COMPLETE
This is a response to the Assignment part of the COURSE.
-->

* Authors: [Laura Colorado](http://www.YOURPAGE.xxx), [NAME_n](http://www.YOURPAGE.xxx)
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

How can different Prompt Engineering techniques, such as Few-Shot Prompting and Meta-Prompting, enhance automated Requirement Analysis for an Etsy-like online marketplace?

## Arguments

#### What is already known about this topic

Requirement Analysis in software development ensures that technical, security, and functional needs are properly defined. When combined with Prompt Engineering techniques like Few-Shot and Meta-Prompting, AI-generated Requirement Analysis can be enhanced for greater accuracy and clarity. Few-Shot Prompting helps models identify patterns by using examples, while Meta-Prompting allows AI to create structured prompts before executing the primary task.

#### Challenges
For Few-Shot Prompting to be effective, high-quality examples are essential for producing strong outputs. Meta-Prompting, while offering a structure-driven approach to AI-generated Requirement Analysis, requires more computational resources, which reduces efficiency in CPU-limited environments. Since Meta-Prompting focuses on structure rather than specific content, it may produce overly generalized requirement lists, potentially missing context-specific details. As a result, human review is necessary to ensure the accuracy of the given output.

#### Opportunities
Refining Few-Shot examples can make AI-generated requirement lists more detailed and better aligned with specific use cases. Combining Meta-Prompting with other techniques can improve the automation and efficiency of Requirement Analysis, making it more adaptable to different projects.

#### What this research is exploring

* We employ Few-Shot Prompting to improve AI-generated Requirement Analysis by providing structured examples that guide the model in recognizing patterns more accurately.
* We use Meta-Prompting to generate structured prompts, allowing AI to create more organized and clear Requirement Analyses.
* We're looking at how combining these techniques can make Requirement Analysis more accurate, scalable, and adaptable for different projects. We're also comparing the processing demands of Meta-Prompting and Few-Shot Prompting, especially on systems with limited CPU power.

#### Implications for practice

* It will be easier to create clear and complete Requirement Analyses with less human effort.
* It will make AI-driven Requirement Analysis faster and reduce the need for manual work.
* We will learn how different Prompt Engineering techniques affect this process to improve AI workflows.
* This research could help develop better AI tools for automating software planning and documentation.

# Research Method

Our reserach involves testing how Few-Shot Prompting and Meta-Prompting can improve AI-driven Requirement Analysis for an Etsy-like marketplace. These are the following steps taken:

1. Creating Test Cases – We set up real-world examples of Requirement Analysis to use as a guide.
2. Using Few-Shot Prompting – We give the AI examples to see if it can learn patterns and generate better results.
3. Using Meta-Prompting – We create structured prompts that help the AI organize its response more clearly.
4. Comparing Results – We look at how well each technique works in terms of accuracy, clarity, and efficiency
   Note: Tests were run on a CPU-limited system, so we optimized the approach to ensure efficient performance while testing.
6. Analysis – We check the AI’s responses to see where they can be better and make adjustments.
7. Refining  – We tweak our methods to make the process more effective for different projects.

# Results

Describe the results achieved through your research process.

# Further research

*Combining Techniques: Testing how other methods (like Chain-of-Thought, Few Shots, etc.) can work together for better results without using too much computing power.
*Smarter AI Prompts: Creating AI models that adjust their approach based on available resources and project complexity.
*Testing Different AI Models: Running the same prompts on different AI models to compare accuracy, speed, and efficiency based on our CPU-limited setup.
*Using AI in Real Projects: Applying these techniques in real software projects to see how well they work in actual development.

By looking into these areas, we can make AI tools more useful for automating software planning and documentation.
