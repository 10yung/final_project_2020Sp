# IS590_Final_Project - Mobot
Description : This porpose of building this project is to create a data science pipe line application,
and functionality will include from the data collection, data cleaning and all the way to the model evaluation.

Team Members : Teng Yung Lin, Henry, Jane

# How to use
1. Install all dependent packages from `requirement.txt` file
2. Rename `exection_plan.yaml.template` into `exection_plan.yaml`
3. Edit the detail of `exection_plan.yaml`
    - Source file directory
    - Imputation, transformation methods
    - Train, test split method
4. Run `python init.py` to construct the folder structure for Mobot project
5. Run `python main.py` to execute the experiments
6. The result file will be inside `./data/estimate` folder which shows the model performance of each experiment.