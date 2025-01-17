# Multimodal-Sacarsm-Detection-on-Vietnamese-Social-Media-Texts
My solution to Group B - UIT Data Science Challenge 2024

Find out more about the competition: https://dsc.uit.edu.vn/bang-b/

Task Overview: 
- Task: Detecting sacarsm from social multimedia data. 
- Input: An image and a caption. 
- Output: A label from 4 classes: MULTI-SARCASM, IMAGE-SARCASM, TEXT-SARCASM and NON-SARCASM.

Solution Overview:
- The base model consists of a tranformer encoder and a classification head.
- Bagging multiple base models to improve generalization.

Results:
- Consistently stayed in top 5 throughout the Public test phase
- But missed the top 10 in the Private test phase :))
