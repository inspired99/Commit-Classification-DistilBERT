## Multilabel Commit Classification using DistilBERT Task for Application to JetBrains internship 

The task is based on this [article](https://www.researchgate.net/profile/Mohamed-Wiem-Mkaouer-2/publication/348228961_Multi-label_Classification_of_Commit_Messages_using_Transfer_Learning/links/61eacfc2c5e3103375ae596d/Multi-label-Classification-of-Commit-Messages-using-Transfer-Learning.pdf). The goal is to implement approach proposed by authors of the article (or other NLP methods) and try different ideas to improve it.

### Task for Project on Autocompletion of commit messages

The task is to classify commits by maintenance activities. There are 3 categories: Corrective, Adaptive and Perfective. Each commit massage may have more than one label at once. The problem was chosen because such classification is essential for understanding the goal of particular commits, also it would be really significant to distinguish type of the commit by it's message without looking at diffs and comparing them. Developers could use such categories to label their commits and in the future it would be easier to search for commit via label. So, there are both a practical and a research reason.

For solution access [notebook on Kaggle](https://www.kaggle.com/code/xyinspired/distilbert-multi-label-commit-classification/notebook) or check file `distilbert-multi-label-commit-classification.ipynb` (unhappily not all the plots are rendered on GitHub)


