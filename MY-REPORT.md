![GenI-banner](https://github.com/genilab-fau/genilab-fau.github.io/blob/8d6ab41403b853a273983e4c06a7e52229f43df5/images/genilab-banner.png?raw=true)

# {Prompt Engineering Lab}

Experimenting with prompt engineering using zero shot and self ask to construct a solution for requirement analysis.

* Authors: Man Vu
* Academic Supervisor: Daniel Raviv

  
# Research Question 

How well an LLM can come up with a requirement analysis for developing an RPG video game using 2 different techniques?

## Arguments

#### What is already known about this topic

* Zero shot prompting provides LLMs no context to complete the prompt
* Self ask allows the LLM to break down complex prompts into smaller portions and thereby potentially enahce the results

#### What this research is exploring

* Exploring prompt engineering techniques and working with LLMs
* Employ zero shot and self ask prompting

#### Implications for practice

* Tt will be easier to create templates for requirement analyses
* We will better understand how to refine prompts to find better solutions

# Results

With zero shot, the LLM was able to give a solution to the original prompt however, some solutions would be vague depend on the run. Run time total for this was about 10s tota. 

For self ask, the LLM was able to ask questions that breaks down the original prompt. Some instances, needed the LLM to re-ask the questions. When paired the automatically generated questions with the original prompt. The LLM was able to give a more detailed and thoughtful solution to the original prompt. Since there were multisteps in getting the solution, the delay was longer for a total of 12s. 

