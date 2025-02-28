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
* Employ zero shot, self ask prompting, and varying performance parameters

#### Implications for practice

* It will be easier to create templates for requirement analyses
* We will better understand how to refine prompts to find better solutions
* For this assignment: I'm aiming for 9 because I worked with a prompt method that was given, a new prompt method, as well as experiment with varying the hyperparamters with results. 

# Results

With zero shot, the LLM was able to give a solution to the original prompt however, some solutions would be vague depend on the run. Run time total for this was about 10s tota. 

For self ask, the LLM was able to ask questions that breaks down the original prompt. Some instances, needed the LLM to re-ask the questions. When paired the automatically generated questions with the original prompt. The LLM was able to give a more detailed and thoughtful solution to the original prompt. Since there were multisteps in getting the solution, the delay was longer for a total of 12s. 

For parameter variations: 
Varying temperature didn’t seem to make a difference for this prompt perhaps need to re rerun the prompt several times more. This is probably also due to the fact that creativity/randomness is more subjective and hard to gauge. 

Varying num_ctx: the amount of tokens it takes from the previous prompt as context, decreasing num_ctx decreased the time for formulating a response but response was nothing useable and vice versa

Varying num_predict: the amount of tokens that it can have in a response, decreasing this value increased the run time but the response was a short and terse depending on the number of tokens used. Varying this parameter to 200 gave a very thorough response but took more time in general. For this purpose we’d prefer a more thorough reply since we are working with a requirements analysis. More detail is better. 

