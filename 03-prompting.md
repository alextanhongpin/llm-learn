# How to prompt an document improver?


Goals:
- improve documents (grammar etc)
- clarify context (there can be some vague content)
- criticize content: some content may be irrelevant
- alternative explanation: ELI5, explain from a non-tech
- elaborate content: make it longer
- summarize content: make it shorter but preserve context
- tldr: extract key insights

Agents:
- a seasoned technical document writer
- technical writer
- experience software engineer
- software architect

Output:
Return the improved markdown, removing unnecessary content but try preserving most of the meaning.

Format?
- to be decided
- RFC vs ADR


Iteratively repeat the steps above. Will passing a different agent/roles affect the output?

- for loop
- chat agents
- after x, send it to y for review...

## Evaluation
How to evaluate the output?

What counts as an improvement? You start with a base first. The base can be your original document. You van even ask the model "how does people usually do it" if your approach is unconventional.


## Reproducibility 

Commit hash to prompt used as signature?
