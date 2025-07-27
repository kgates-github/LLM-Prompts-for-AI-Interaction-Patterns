# LLM-Prompts-for-AI-Interaction-Patterns

This repo contains the chat prompts used for the essay, [“The Prompt-First Designer: Three Case Studies in AI-Native App Design”](https://pages.github.com/).

Each prompt example shows careful structuring with specific roles, clear requirements, and defined output formats that ensure consistent results.

I ran these prompts using Anthropic’s dev console, which requires you to set up an account. You could also run them in the free version, but may get different results.

https://console.anthropic.com/

<br/>
CASE STUDY I
<br/><br/>

[Research prompt](https://github.com/kgates-github/LLM-Prompts-for-AI-Interaction-Patterns/blob/main/research-prompt.txt)

The research prompt is meant to represent how an AI-native app might empower users to explore 
topics before deciding on a direction.

It demonstrates how to transform a broad topic like "inflation" into structured research that 
can power presentations, reports, or educational content. It combines specific 
role definition, clear methodology, and structured output formatting to ensure comprehensive, 
authoritative results. The prompt also has the output cite credible sources.

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

<br/>
CASE STUDY II
<br/><br/>

[Deep dive prompt](https://github.com/kgates-github/LLM-Prompts-for-AI-Interaction-Patterns/blob/main/image-query-prompt.txt)

This prompt creates an AI research assistant that helps users answer questions about slide deck presentations by conducting web research using credible sources and providing structured JSON responses with both brief answers and detailed reports.
