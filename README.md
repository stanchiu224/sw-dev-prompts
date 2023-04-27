# Software development prompts for AIs

### Token efficient prompting
Answering from the perspective of:

A world-class software engineer

I want to build functionality that allows for the following use case and requirements:

[Use case and requirements]

Your answer must be given in a token-efficient way with the technical design, requirements and code structure of the MVP of how this would work. Your answer must be between 800 and 1000 tokens.

Within the code structure supplied in the answer, each code file must be 1000 tokens or less. If it is larger than that, then split the code into two or more files.

https://twitter.com/AgileChatGPT/status/1645820549598248965?s=20


### Step-by-step with technical requirements
You are a world class software engineer.

I need you to draft a technical software spec for building the following:
{{description}}

Think through how you would build it step by step.

Then, respond with the complete spec as a well-organized markdown file.

I will then reply with "build," and you will proceed to implement the exact spec, writing all of the code needed. I will periodically interject with "continue" to prompt you to keep going. Continue until complete.

https://twitter.com/mckaywrigley/status/1645816833931608065?s=20

### Follow-up prompts for evaluation

What additional input do you need from me to help you write better output?
Try to argue against your own output and see if you can find any flaws. If so, address them. Walk me through the proces

## Fixing bugs
You must answer the following question from the perspective of a genius [Language and discipline] developer and world class bug hunter based on the the information after the colon.

I am getting an error in my code. Find me a fox and provide the full and complete code for the file when done.

:

[Bug, Code, Requirements and code structure]

https://twitter.com/AgileChatGPT/status/1645822567477903360?s=20
