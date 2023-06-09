# SayCan
## Do As I Can, Not As I Say: Grounding Language in Robotic Affordances

Project website: https://say-can.github.io/ 
Paper: https://arxiv.org/abs/2204.01691

**Abstract** Large language models can encode a wealth of semantic knowledge about the world. Such knowledge could be extremely useful to robots aiming to act upon high-level, temporally extended instructions expressed in natural language. However, a significant weakness of language models is that they lack real-world experience, which makes it difficult to leverage them for decision making within a given embodiment. For example, asking a language model to describe how to clean a spill might result in a reasonable narrative, but it may not be applicable to a particular agent, such as a robot, that needs to perform this task in a particular environment. We propose to provide real-world grounding by means of pretrained skills, which are used to constrain the model to propose natural language actions that are both feasible and contextually appropriate. The robot can act as the language model's "hands and eyes," while the language model supplies high-level semantic knowledge about the task. We show how low-level skills can be combined with large language models so that the language model provides high-level knowledge about the procedures for performing complex and temporally-extended instructions, while value functions associated with these skills provide the grounding necessary to connect this knowledge to a particular physical environment. We evaluate our method on a number of real-world robotic tasks, where we show the need for real-world grounding and that this approach is capable of completing long-horizon, abstract, natural language instructions on a mobile manipulator. The project's website and the video can be found at https://say-can.github.io/.

## Instructions

This is a self-contained implementation of SayCan on a table top environment. It should run by running each cell in order.

## QUICK START

Step 1. Register for an OpenAI API key to use GPT-3 (there's a free trial) and enter it below

Step 2. Menu > Change runtime type > Hardware accelerator > "GPU"

Step 3. Menu > Runtime > Run all

----
## Summer Annual Conference of IEIE, 2023

- A paper analyzing the performance of using the SayCan simulator to generate plans using GPT models and Chain-of-thought prompts. 

- [paper](https://github.com/ohnghb99/tabletop-SayCan/blob/main/2023_paper_hyobinong.pdf)

- The full chain-of-thought prompts used in the experiment can be found [here](https://github.com/ohnghb99/tabletop-SayCan/blob/main/Chain-of-thought%20prompt.md).
