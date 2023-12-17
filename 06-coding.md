# What are some other usecases for LLM in coding


- converting between different programming languages. e.g. i have a library in python that i want to rewrite in golang
- suggesting code structure, like designing pipelines
- optimize: we can ask llm to optimize the code, e.g. by first determining the space and time complexity
- variation: ask for different variation of the code
- sql generation


There are some limitations that needs to be overcome for sql generation. We can use slash commands to guide the model to get to the solution, e.g.

- find similar schema
- find foreign keys
- find index to be used for query
- optimize query by running explain analyze and checking slow query
- disable delete or truncation (sql injection)
- combine with other tools like prettier, and sql ast parser, we can validate the code before executing
