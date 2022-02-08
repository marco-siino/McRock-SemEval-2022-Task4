# McRock-SemEval-2022-Task4-Submission1
This repo contains data and code for our first submission to solve SemEval-2022 Task 4: Patronizing and Condescending Language Detection
For detailed description of our models, please see the paper "McRock at SemEval-2022 Task 4: Patronizing and Condescending
Language Detection using Multi-Channel CNN and DistilBERT" by M.Siino et al.

## SubTasks Description 
* Subtask 1: Binary classification. Given a paragraph, a system must predict whether or not it contains any form of PCL. 

* Subtask 2: Multi-label classification. Given a paragraph, a system must identify which PCL categories express the condescension. Our PCL taxonomy has been defined based on previous works on PCL. We consider the following categories:

  ** Unbalanced power relations.

  ** Shallow solution. 

  ** Presupposition. 

  ** Authority voice. 

  ** Metaphor. 

  ** Compassion. 

  ** The poorer, the merrier. 
  
## Code
The following code can be execute on Google Colab.

* SubTask 1 Notebook: **SemEval2022_Task4_SubTask1_Submission1_MSiino_MultiCNN**.ipynb
* SubTask 2 Notebook: **SemEval2022_Task4_SubTask2_Submission1_MSiino_DistilBERT**.ipynb

## Useful Links
* [Task description paper](TBD)
* [Official website](https://sites.google.com/view/pcl-detection-semeval2022/) of the task
