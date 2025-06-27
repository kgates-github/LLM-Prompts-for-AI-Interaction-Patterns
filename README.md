# LLM-Prompts-for-AI-Interaction-Patterns

This repo contains the chat prompts used for the essay, [“The Prompt-First Designer: Three Case Studies in AI-Native App Design”](https://pages.github.com/).

Each prompt example shows careful structuring with specific roles, clear requirements, and defined output formats that ensure consistent results.

I ran these prompts using Anthropic’s dev console, which requires you to set up an account. You could also run them in the free version, but may get different results.

https://console.anthropic.com/




CONTENTS

[Research prompt](https://pages.github.com/)

The research prompt demonstrates how to transform a broad topic like "inflation" into structured research that can power presentations, reports, or educational content.

[Presentation prompt](https://pages.github.com/)

This prompt takes the JSON object with findings from the research prompt and creates a slide presentation.

[Theme and style prompt](https://pages.github.com/)

This prompt takes a slide deck outline and comes up with themes that capture the essence of the content. It then creates a matrix of themes and styles to be used to generate image search queries.

[Image query prompt](https://pages.github.com/)

This prompt takes a matrix of themes and styles and generates search queries to be used with image search APIs. 

Note: This prompt creates queries based on the whole slide deck, which is appropriate for finding images for the intro slides, but it might be more effective to have queries created for each section, or even each slide.
