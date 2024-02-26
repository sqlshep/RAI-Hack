# RAI Getting Started

[**Microsoft’s framework for building AI systems responsibly**](https://blogs.microsoft.com/on-the-issues/2022/06/21/microsofts-framework-for-building-ai-systems-responsibly/)

[**Responsible AI Maturity Model**](https://www.microsoft.com/en-us/research/publication/responsible-ai-maturity-model/)

[**Responsible AI Impact Assessment Guide**](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Guide.pdf)

[**Responsible AI Impact Assessment Template**](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Template.pdf)

[**Assess AI systems by using the Responsible AI dashboard**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai-dashboard?view=azureml-api-2)

[**Getting started with Azure Machine Learning Responsible AI components (Part 1)**](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/getting-started-with-azure-machine-learning-responsible-ai/ba-p/3746948?WT.mc_id=aiml-71289-ruyakubu)

[**RAI Dashboard Supported scenarios and limitations**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai-dashboard?view=azureml-api-2#supported-scenarios-and-limitations)

[**Responsible AI Accelerator**](https://github.com/Azure/azureml-examples/tree/main/sdk/python/responsible-ai)

[**RAI for Azure AutoML**](https://github.com/Azure/azureml-examples/blob/main/sdk/python/jobs/automl-standalone-jobs/automl-classification-task-bankmarketing/automl-classification-task-bankmarketing-serverless.ipynb)

[**Responsible AI: The research collaboration behind new open-source tools offered by Microsoft**](https://www.microsoft.com/en-us/research/blog/responsible-ai-the-research-collaboration-behind-new-open-source-tools-offered-by-microsoft/)

[**Responsible AI Toolbox**](https://github.com/microsoft/responsible-ai-toolbox)

[**Responsible AI with LLMs**](https://github.com/Azure/FTALive-Sessions/blob/main/content/ai/responsible-ai/en/responsible-ai-for-llms.md)

[**Configure content filters with Azure OpenAI Service**](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/content-filters)

[**Video - Azure Responsible AI Dashboard**](https://youtu.be/hXq-KHHkJvk)



## To get strated with the Solution Accelerator 

1. From your Azure Machine Learning(AML) compute instance, start a Jupyter Session, then open a terminal session from the Upper right drop down menu "New"

     ![Open Terminal.](/images/Terminal.png)

  Clone the following github repo 
  ```
  git clone https://github.com/sqlshep/RAI-Hack.git
  ```

2. Navigate to the newly cloned folder in Jupyter or VS Code and select the folder of the project you would like to work on,**"Diabetes_Story"**, **"Education_Story"**, **"Finance_Story"** or **"Healthcare_Story"**.  Then select the .ipynb notebook in that folder and start working.

   Keep in mind that each notebook takes about 30 minutes in total to run. While it is running you can monitor the model training and RAI dashboard creation phase in the AML portal under Pipelines, there will be two pipelines created. 

3. Once complete, Navigate to Models in teh AML Portal and select the most recent model created;

   
     ![AML Model selection.](/images/ModelsList.png)



For a deep Dive into the RAI Dashboard 
[Getting started with Azure Machine Learning Responsible AI components](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/getting-started-with-azure-machine-learning-responsible-ai/ba-p/3746948?WT.mc_id=aiml-71289-ruyakubu)
