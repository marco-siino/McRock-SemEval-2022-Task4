# McRock-SemEval-2022-Task4
This repo contains data and code for our two submissions to solve SemEval-2022 Task 4: Patronizing and Condescending Language Detection. 
For detailed description of our models, please see the paper "McRock at SemEval-2022 Task 4: Patronizing and Condescending Language Detection using Multi-Channel CNN, Hybrid LSTM, DistilBERT and XLNet" by M.Siino et al.

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
The following code can be executed on Google Colab.

* SubTask 1 Notebook: **SemEval2022_Task4_SubTask1_Submission1_MSiino_MultiCNN**.ipynb
* SubTask 1 Notebook: **SemEval2022_Task4_SubTask1_Submission2_MSiino_HybridLSTM**.ipynb
* SubTask 2 Notebook: **SemEval2022_Task4_SubTask2_Submission1_MSiino_DistilBERT**.ipynb
* SubTask 2 Notebook: **SemEval2022_Task4_SubTask2_Submission2_MSiino_XLNet**.ipynb

## BIBTEX
@inproceedings{siino2022mcrock,
  title={McRock at SemEval-2022 Task 4: Patronizing and Condescending Language Detection using Multi-Channel CNN, Hybrid LSTM, DistilBERT and XLNet},
  author={Siino, Marco and La Cascia, Marco and Tinnirello, Ilenia},
  booktitle={Proceedings of the 16th International Workshop on Semantic Evaluation (SemEval-2022)},
  pages={409--417},
  year={2022}
}

## Useful Links
* [Description paper](https://aclanthology.org/2022.semeval-1.55/)
* [Official website](https://sites.google.com/view/pcl-detection-semeval2022/) of the task
