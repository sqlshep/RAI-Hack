# RAI-Hackathon-2023
RAI Hackathon 2023

1. From your Azure Machine Learning(AML) compute instance, start a Jupyter Session, then open a terminal session from the Upper right drop down menu "New"

     ![Open Terminal.](/images/Terminal.png)

  Clone the following github repo 
  ```
  git clone https://github.com/microsoft/ResponsibleAIAccelerator
  ```

2. Navigate to the newly cloned folder in Jupyter or VS Code and select the folder of the project you would like to work on, **"Education_Story"**, **"Finance_Story"** or **"Healthcare_Story"**.  Then select the .ipynb notebook in that folder and start working.

   Keep in mind that each notebook takes about 30 minutes in total to run. While it is running you can monitor the model training and RAI dashboard creation phase in the AML portal under Pipelines, there will be two pipelines created. 

3. Once complete, Navigate to Models in teh AML Portal and select the most recent model created;

   
     ![AML Model selection.](/images/ModelsList.png)


This site was built using [GitHub Pages](https://pages.github.com/).

For a deep Dive into the RAI Dashboard 
[Getting started with Azure Machine Learning Responsible AI components](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/getting-started-with-azure-machine-learning-responsible-ai/ba-p/3746948?WT.mc_id=aiml-71289-ruyakubu)
