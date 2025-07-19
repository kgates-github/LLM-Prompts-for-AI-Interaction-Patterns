# LLM-Prompts-for-AI-Interaction-Patterns

This repo contains the chat prompts used for the essay, [Embracing Design’s AI-Native Frontier: Case Studies in Computational Design Thinking](https://medium.com/@kevinagates/embracing-designs-ai-native-frontier-case-studies-in-computational-design-thinking-30c394a78b7e).

I ran these prompts using Anthropic’s dev console, which requires you to set up an account. You could also run them in the free version, but may get different results.

https://console.anthropic.com/

<br/>
CONTENTS
<br/><br/>

[Research prompt](https://github.com/kgates-github/LLM-Prompts-for-AI-Interaction-Patterns/blob/main/research-prompt.txt)

The research prompt is meant to represent how an AI-native app might empower users to explore 
topics before deciding on a direction.

It demonstrates how to transform a broad topic like "inflation" into structured research that 
can power presentations, reports, or educational content. 

Output from this prompt produces a broad perspective on inflation over the last 10 years. When 
we create the slide deck (using the presentation prompt), we ask the LLM to focus on a topic 
of interest: the effects of COVID-19 on inflation.

[Presentation prompt](https://github.com/kgates-github/LLM-Prompts-for-AI-Interaction-Patterns/blob/main/presentation-prompt.txt)

This prompt takes the JSON object with findings from the research prompt and creates a slide presentation. Being able to craft UX with LLM-simulated content is key.

[Theme and style prompt](https://github.com/kgates-github/LLM-Prompts-for-AI-Interaction-Patterns/blob/main/theme-and-style-prompt.txt)

This prompt takes a slide deck outline and comes up with themes that capture the essence of the content. It then creates a matrix of themes and styles to be used to generate image search queries.

[Image query prompt](https://github.com/kgates-github/LLM-Prompts-for-AI-Interaction-Patterns/blob/main/image-query-prompt.txt)

This prompt takes a matrix of themes and styles and generates search queries to be used with image search APIs. 

Note: This prompt creates queries based on the whole slide deck, which is appropriate for finding images for the intro slides, but it might be more effective to have queries created for each section, or even each slide.
