# AutoML_LLM
Realizing AutoML with LLM

We present a novel method for evaluating the reasoning capabilities of LLMs. Our method
asks LLMs to generate a set of empirical rules for classification problems, which can have
applications in important areas such as medical diagnosis.

## Re-producing our results
To re-produce our results, you need to have access to ChatGPT 3.5, ChatGPT 4, and Claude 2.

You may design your prompts as the examples in the **prompt** folder of this repo. You may test the rules' accuracy as in **GPT3.5_RobustnessTest** in the **result** folder.

## Run our code
You may simply run our code using Jupyter, based on generated rules included in **GPT3.5_RobustnessTes** and **breast_disease_experiment** in the result folder. Please be reminded that you should replace the path of the dataset with yours. The environment required is

Python >= 3.9\
Jupyter Notebook >= 6.3.0\
Pandas >= 2.0\
Numpy >= 1.26
