# Base Concepts

## Role

- _Who am I?_
- Instead of describing everything it might be easier to just define a role.
- Example: "You are an expert Rust developer."

## Context

- _What are we doing?_
- Repeat the most important parts.
- Do not include anything that might disturb the focus or misleads to wrong direction.
- Be precise.
- Be careful with restrictions, don't keep them too long. The focus might shift to list of restrictions for example, if there are list of banned words those might disturb the focus so, response might include those.
- Try to use positive wording instead of negative wording. For example, "Instead of requesting an image of a room without any furniture, ask for an empty room." [Some more information.](https://richardkovacs.dev/blog/optimistic-prompting)

## Input

- _What are we operating on?_
- If we have data then better to describe the input. How is it look like, what it is etc.
- Example: "This is information about employees where some rows might be missing data of some of the columns."

## Output

- _What do you expect?_
- Clearly state your intention for the desired output.
    - What format should it be? e.g. list, step by step guide, code example.
    - What style/type of the output you want? e.g. tone, length, explanation.
- If possible, give examples.
- Example: "Provide code example with brief explanation with a list of the functions used from the standard library."

## Restrictions

- _How should I do it?_
- Provide clear boundaries.
- Example: "Use only C++17 and the standard library."

## Scope

- AI is good with abstract ideas, it might get hard time to split complex parts to smaller bits logically.
- It might be easier to break down to smaller sections by yourself and provide those one by one.
