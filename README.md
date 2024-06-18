[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/UpfcA4qp)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292862&assignment_repo_type=AssignmentRepo)
# SE-Assignment-3
Assignment: Introduction to Prompt Engineering
Instructions:
Answer the following questions based on your understanding of prompt engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Definition of Prompt Engineering:

What is prompt engineering, and why is it important in the context of AI and natural language processing (NLP)?
Components of a Prompt:Prompt engineering is the process of iterating a generative AI prompt to improve its accuracy and effectiveness. For example, if you're using ChatGPT to brainstorm a professional summary while refining your resume, you might write a command like, “Write a sample professional summary for a marketing analyst.” You might prompt ChatGPT’s response with feedback like “too formal” or “shorten to less than 100 words.”  It is important because  for AI engineers to create better services, such as chatbots that can handle complex tasks like customer service or generate legal contracts. Making sure that generative AI services like ChatGPT are able to deliver outputs requires engineers to build code and train the AI on extensive and accurate data.



What are the essential components of a well-crafted prompt for an AI model? Provide an example of a basic prompt and explain its elements. 
Simple and Iterate. Overview
Use Clear Instructions
Be Detailed and Specific
Avoid Impreciseness
Use examples.
Consider tone and audience.
Eg: Write a love poem to a dying lover thats not less than 100 words and not more than 200 words.
Types of Prompts:

Describe different types of prompts (e.g., open-ended prompts, instructional prompts). How does the type of prompt influence the AI model's response?
Text Generation Prompts: Used to generate texts on a specific topic
Question Answering Prompts: used to answer a question or solve a problem
Code Generation Prompts: generates lines of code for specific programes and may explain issues with already written code

Prompt Tuning:

What is prompt tuning, and how does it differ from traditional fine-tuning methods? Provide a scenario where prompt tuning would be advantageous.
Prompt tuning is a technique used to improve the performance of a pre-trained language model without modifying the model's internal architecture. It is different from  traditional fine-tuning methods because traditional fine-tuning embeds data into the model's architecture, essentially 'hardwriting' the knowledge, which prevents easy modification
prompt tuning is able to  enhance the performance of a pre-trained language model without altering its core architecture
Role of Context in Prompts:

Explain the role of context in designing effective prompts. How can adding or omitting context affect the output of an AI model?
Context allows for the AI to understand the exact result wanted bt the user to ensure refined output
Adding or ommitting context could change the meaning behind the instructions which also change the expected results
Ethical Considerations in Prompt Engineering:

What ethical issues should be considered when designing prompts for AI systems? Discuss potential biases and how they can be mitigated.
Privacy - though image generation one can invade ones privacy and go as far as generating nude pictures of people
Biasness- in image generation, AI has been seen to be unable in some instances to generate images of Africans or black people, this shows  a level of biasness in its system. This can be reversed via reworking AI to identify all races. AI should also have algorithms that gather information beyond that which is considered majority thus providing output for all demographics of people

Evaluation of Prompts:

How can the effectiveness of a prompt be evaluated? Describe some metrics or methods used to assess prompt performance.
Through cretiria such as
Usefullness of output
degree of biasness
specificity
metric methods include
accuracy
precision
create unit tests with a list of pair “context,prompt template,expected output” and compare expected output vs real output with a LLM
use human evaluation - using reviews and feedbacks

Challenges in Prompt Engineering:

Identify and discuss common challenges faced in prompt engineering. How can these challenges be addressed?
Common challenges include:
Data Sensitivity: Any minor context shift changes the output by a large margin
Model Generalization: a massive requirement for specificity means that any deficiency resuits in generalized outputs
Communication Barriers: most AI will require the user to speak english thus one who does not will be unable to use it
Biased Datasets: biasness in the data collection and algorithm may lead to unwanted results
These challenges can be solved by updating AI to use algoritymns that collect information from both the minority and majority clusters
Having AI that can translate all languages

Case Studies of Prompt Engineering:

Provide an example of a successful application of prompt engineering in a real-world scenario. What were the key factors that contributed to its success? copilot an AI used bt programmers is an application of prompt engineering that has easened software development, this makes it easier and faster to finish and debug projects

Future Trends in Prompt Engineering:

What are some emerging trends and future directions in the field of prompt engineering? How might these trends shape the development of AI and NLP technologies?
Constant development in image generating AI and voice driven AI is a common trend, people giving instructions using their voice and AI being able to hold a logical conversation and giving back relatively accurate output show immense development
This means in future people may be unable to tell the difference between a persons voice and AI, this may lead to security breaches and more


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
