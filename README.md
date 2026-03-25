# LLM Prompts

This repository is a collection of prompts for working with LLMs. 
Some are original, others are adapted from ideas I found and refined over time through actual use.

## How to Use These Prompts

1. Choose your tool: Most LLMs (ChatGPT, Claude, Gemini) have a settings area for "Custom Instructions" or "System Prompts."
2. Set your defaults: Copy a file from the standing_instruction folder into that settings area to give the AI a permanent "personality."
3. Run specific tasks: For one-off needs (like summarizing an article), copy a prompt from the single_tasks folder directly into your active chat.

> [!TIP]
> 
> If your LLM supports "Projects," you can upload these .md files directly to give the AI context for a specific workspace.

### Standing Instructions

Most LLM tools let you define standing instructions—persistent guidelines that shape how the model responds across conversations (for example: tone, level of detail, or formatting rules). 
Many tools also support project-specific instructions, which allow you to tailor behavior even further. 
The `standing_instruction` prompts in this repo are designed for that purpose.

Because many tools impose character limits, each prompt is 1,500 characters or fewer and ready to copy/paste.

- `global_default.md` — Baseline instruction set covering the core behaviors I want from an LLM. Use this as a starting point.
- `minimalist_utility.md` — Optimized for fast, no-frills answers. Useful when you want minimal verbosity.
- `brainstormer.md` — Helps expand, challenge, and stress-test ideas in a structured way.
- `researcher.md` — Guides the model to act as a structured research assistant (summaries, sources, synthesis).
- `coding_tasks.md` — Focuses the model on writing, reviewing, and refining clean, readable code.

### Single-Task Prompts

The rest of the prompts are designed for one-off tasks. 
Unlike standing instructions (which shape ongoing behavior), these are meant to be used as needed. 
These prompts can be used while standing instructions are still in place.

- `article_summary.md` — Generates short summaries to make saved articles easier to scan later.
- `bibliography_in_cse_format.md` — Formats sources in CSE (Council of Science Editors) style for quick bibliography entries.
- `manuscript_review.md` — Performs mechanical edits on manuscripts before human review.
- `news_story_summary.md` — Summarizes news stories with a structure suited for quick reading.
- `text_editing_rules.md` — A reusable set of editing rules for improving clarity and consistency in text.

## License

This project is released under the MIT License. 
The prompts are a mix of original work and adapted ideas, shared here for general use.

# A quick note on using LLMs

I use LLMs because they're powerful and useful tools. 
Still, I'm skeptical about the impact of LLMs, particularly as regards creative work. 
You'll notice none of these prompts creates content. That’s deliberate. 
The writing, the creating—that's the fun part.

That's what makes reading worthwhile.

There’s a real risk that human creativity will become viewed as inefficient, old-fashioned, and unnecessary. 
That would be a real loss. 
I am aware that by sharing these prompts, I may be contributing to the proliferation of LLMs. 
It’s a tricky balance, one I’m certain I need to work on.

All I can say is: 
Please, respect your creativity and human voice.
Authenticity trumps perfection.
