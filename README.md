# comm4190_F25_Tutor_Task
## Testing LLM as a Guitar Tutor
I asked gpt-4 to be a guitar tutor. This repository contains my interaction with gpt 4 as my guitar tutor under the structured and non structured prompts. I also refine the prompt to modify gpt-4's tutoring behavior and communciation to my desired way. 

This repository contains the following files:
- **'no_prompt.ipynb'**: a python notebook that includes my conversation with gpt-4 tutor without a structured prompt.
     - In the 15 minute conversation, I stayed on task for the first half of the conversation and then in the second tried some distraction techniques (i.e. a unmotivated student who doesn't want to learn, ask irrelevant questions, try and distract the tutor, etc.).
- **'with_prompt.ipynb'**: a python notebook that includes my conversation with gpt-4 tutor with a structured prompt.
     - same as  the unstructured session, I tested it by staying on track and starting to distract towards the second half of the conversation. 
- **'evaluation_and_finetuning.ipynb'**: a python notebook that contains
  1) my evaluation of the two sessions in terms of: a) My subjective experience of being tutored in both sessions b) Observations on particular wording in the responses from the LLMs in both sessions and evaluation of how well they represent appropriate tutoring communication.
  2) My own modifications to the Tutoring prompt to try and fine tune and improve the behave and use it in a new session to test out whether my changes improved the tutoring behavior and communication.
- **'modified_prompt.ipynb'**: a python notebook that contains 30 minute of testing interaction with gpt4 after the prompt has been updated for desired tutoring behaviors and communications.