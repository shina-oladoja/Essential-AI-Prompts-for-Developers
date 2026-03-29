# Stepwise Chain of Thought Prompt

This simply means asking the model to simply break things up in a step to go "one step aa a time".

## example of a verbose prompt

The example below shows a verbose prompt that has a no stepwise or breakdown of code or project and can leads to missing parts of the project or code. In a nutshell, the project or feature, or function or codeblock has no lead or direction and might also be hard to debug latter or refined and basically extend little parts of it to another direction.

### verbose example

"help me refactor the code in #file:vehiclesServices.ts"

### right example

"help me refactor the code in #file:vehiclesServices.ts. Go one step at a time. Do not move to the next step until I give the keyword "next". Begin"

#### Note

While following the prompt, there might be some changes during the interaction with the AI, just find a way to make it get back to primary instruction.