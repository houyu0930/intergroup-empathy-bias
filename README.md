# Studying *Intergroup Empathy Bias* in Large Language Models

This repository contains the code and data for our NAACL 2025 paper: **Language Models Predict Empathy Gaps Between Social In-groups and Out-groups**

## Abstract

Studies of human psychology have demonstrated that people are more motivated to extend empathy to in-group members than out-group members (Cikara et al., 2011). In this study, we investigate how this aspect of intergroup relations in humans is replicated by LLMs in an emotion intensity prediction task. In this task, the LLM is given a short description of an experience a person had that caused them to feel a particular emotion; the LLM is then prompted to predict the intensity of the emotion the person experienced on a numerical scale. By manipulating the group identities assigned to the LLM's persona (the "perceiver") and the person in the narrative (the "experiencer"), we measure how predicted emotion intensities differ between in-group and out-group settings. We observe that LLMs assign higher emotion intensity scores to in-group members than out-group members. This pattern holds across all three types of social groupings we tested: race/ethnicity, nationality, and religion. We perform an in-depth analysis on Llama-3.1-8B, the model which exhibited strongest intergroup bias among those tested.

## Code

We provide the code for the emotion intensity prediction tasks and analysis, with prompts and experiment results.

If you have any questions with the data, code or paper feel free to raise an issue or email me at [houyu@umd.edu](mailto:houyu@umd.edu). Thank you!