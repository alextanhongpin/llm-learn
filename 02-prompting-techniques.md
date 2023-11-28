# Prompting Techniques

Remember, the LLMs only completes the next word based on the highest probability.

https://www.promptingguide.ai/techniques

## Chain-of-Note

```markdown
A.3 INSTRUCTION PROMPTS

(1) For standard RALM, the instruction is:

Task Description: The primary objective is to briefly answer a specific question.

(1) For RALM with CON, the instruction is:

Task Description:

1. Read the given question and five Wikipedia passages to gather relevant information.

2. Write reading notes summarizing the key points from these passages.

3. Discuss the relevance of the given question and Wikipedia passages.

4. If some passages are relevant to the given question, provide a brief answer based on the passages.

5. If no passage is relevant, direcly provide answer without considering the passages
```

https://arxiv.org/abs/2311.09210
