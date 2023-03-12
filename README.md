# Dataset for studying Error-related EEG Potentials in Human-Agent-Collaboration 
## Dataset description
This dataset contains data from 11 subjects that took part in a Human-Agent Collaboration experiment that in the future could be used for Brain-Computer Interface applications. 

The human, in collaboration with an agent, was given the task to bring an object to a goal by following a marked trajectory in a grid-world game.

The experiment contained two collaboration scenarios: 
1. *Shared workspace*: the workspace was divided into two areas colored in 2 different colors (either blue or green). The human controlled the object movements in one of the areas and the agent in the other area. The idea behind this scenario was to simulate collaboration on the same task, with object hand-over between a human and an agent.
2. *Shared responsibility*: over the whole workspace both the human and the agent controlled the movement of the object, but only in two directions (e.g. only up and left) out of the four possible directions (up, down, left, and right). This scenario simulated a collaboration on the same task, where both the human and the agent physically and sequentially interacted with the object at the same time.

The dataset is further described in the study [Brain computer interface to distinguish between self and other related errors in human agent collaboration](https://t.co/LUQLMKVs6S). In the main section of the paper, the results are excluding the data from subject id4 (which are separately reported in the Supplementary Information).

## Triggers description
The data contains the triggers that mark the beginning of an event. Here is the meaning of the trigger codes:
- *R5*: Start of shared responsibility block
- *R6*: Start of shared workspace block
- *S10*: End of block
- *S15*: Start of episode

- *S1*: the position of the target is upwards, relative to the current position of the moving object
- *S2*: the position of the target is to the right, relative to the current position of the moving object
- *S3*: the position of the target is downwards, relative to the current position of the moving object
- *S4*: the position of the target is to the left, relative to the current position of the moving object

- *R1*: the subject pressed the "up" button
- *R2*: the subject pressed the "right" button
- *R3*: the subject pressed the "down" button
- *R4*: the subject pressed the "left" button

- *S5*: the moving object correctly moved upwards
- *S6*: the moving object correctly moved to the right
- *S7*: the moving object correctly moved downwards
- *S8*: the moving object correctly moved to the left

- *S11*: the moving object wrongly moved upwards
- *S12*: the moving object wrongly moved to the right
- *S13*: the moving object wrongly moved downwards
- *S14*: the moving object wrongly moved to the left

If you have any questions regarding the data or the study, feel free to contact me (contact details can be found [here](https://www.mirmi.tum.de/mirmi/team/dimova-edeleva-viktorija/)). 

## Citation
If you use this dataset, please give credit to:

Dimova-Edeleva, V., Ehrlich, S. K., & Cheng, G. (2022). Brain computer interface to distinguish between self and other related errors in human agent collaboration. Scientific Reports, 12(1), 20764.
