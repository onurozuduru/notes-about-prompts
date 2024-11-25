# Notes About Prompts

## Why?

I generally use AI tools for development related tasks.
I realized that time to time I was checking different sources from the internet for useful prompts while using those tools.
After that realization moment, I decided to collect such information as a note in my GitHub repo for my personal usage.

Thankfully, there are many examples for prompting. However, I want to focus on zero-shot examples that I can survive with small additions to my main task.

Long story short, I decided to collect few tips and prompt examples focused on my daily usage and easy access from every environment.

## A General Reminder 

- No matter what LLMs will respond.
- The response is reflection of the quality of the input.
- They cannot change their mind in middle of the process, they always focus on the next part.

## Base Concepts

I collected some basic information in this file: [BasicConcepts.md](BasicConcepts.md)

## Collection of Zero-Shot Prompts

### Chain of Thought

- "Let’s break this down step-by-step and explain each part clearly, ensuring each step builds toward a cohesive solution: `PROMPT`"
- "Divide this into smaller tasks. For each part, explain what needs to be done and why it matters to the overall solution: `PROMPT`"
- "Solve this by explaining each step in detail, providing examples where necessary, and summarizing how they lead to the final solution: `PROMPT`"
- "Explore multiple reasoning paths for this. Brainstorm approaches, explain the reasoning, and narrow down to the most effective solution: `PROMPT`"
- "Guide through this task step-by-step, anticipating challenges and suggesting strategies to address them as you progress toward the solution: `PROMPT`"

### Critique and Evaluation

- "For the given task, generate several solutions. For each, explain its key aspects, list pros and cons, and compare it to alternatives before recommending the best option. The task: `PROMPT`"
- "`PROMPT`. Critique multiple approaches, identify strengths and weaknesses, and rank them based on effectiveness."
- "`PROMPT`. Assess this by comparing it to similar scenarios, highlighting key differences, and give insights to improve the response."

### Simulated Expert Discussions

- "Imagine a panel of experts discussing this task. Each expert offers unique insights, and you synthesize their recommendations into a final solution: `PROMPT`"
- "Solve this task collaboratively by simulating a debate among personas. Critique each other’s ideas until a consensus is reached: `PROMPT`"
- Prompt from [PanelGPT](https://github.com/holarissun/PanelGPT):
	- [Query-Dependent Prompt Evaluation and Optimization with Offline Inverse RL](https://openreview.net/forum?id=N6o0ZtPzTg)
	- [Reinforcement Learning in the Era of LLMs: What is Essential? What is needed? An RL Perspective on RLHF, Prompting, and Beyond](https://arxiv.org/abs/2310.06147)
> 3 experts are discussing the question with a _panel_ discussion, trying to solve it step by step, and make sure the result is correct _and avoid penalty_: `PROMPT`


### Tailored Explanation for Learning

- "Explain this concept for an audience of `ROLE`. Use a relatable example to introduce the topic, then dive into details to ensure clarity and engagement for that audience: `PROMPT`"
- "Summarize this by starting with an overview of the main concept, addressing potential challenges, and suggesting strategies to overcome them: `PROMPT`"

### Creative Problem Solving and Refinement Technique

- "Develop three creative solutions. For each, provide details, address challenges, and refine the idea before selecting the best one for the task: `PROMPT`."
- "`PROMPT`. Create a network of ideas, starting with the main concept, and map how related ideas or steps connect to form a comprehensive solution."

## Collection of Different Techniques for Future Reading

I collected multiple interesting techniques in this file: [CollectionOfTechniques.md](CollectionOfTechniques.md)

# References
- https://www.promptingguide.ai/techniques
- https://github.com/ai-boost/awesome-prompts
- https://blog.tomparish.com/cpJXPMa0lSSkoU
- https://medium.com/@jordan_gibbs/the-most-important-chatgpt-prompt-55ef2bdc4d4a
- https://medium.com/@tparish/when-you-prompt-its-ok-to-ask-for-what-you-want-069a0308f82c
- https://www.superside.com/blog/chatgpt-prompts
