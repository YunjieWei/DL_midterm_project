Yuxin Jiang (yj3035)
Yunjie Wei (wy8964)
Yihan Cao (yc7683)

I. 1_compare_parameters.ipynb contains the code for finding the optimal parameters.
In stage1, we determine the best Prompt, and through this process, we confirmed that V4 is the optimal one.
The subsequent code is used to find the best parameters corresponding to V4.
Each of the three team members ran the model with different parameter settings to obtain the corresponding accuracy and model.

II. 2_generate_csv.ipynb is used to generate the submission CSV file based on the models trained with relatively better parameters.

III. Both 1 and 2 were used in our actual experiments, while 3_final_code.ipynb combines the contents of the first two files and serves as the final submission code.
The function run_stage1() is taken from the first notebook and is only used during the model selection stage; it does not need to be run when training the final model.

IV. 4_example.zip contains some of the corresponding submission.csv.

V. 5_experiment_results.json stores the accuracy results obtained under different parameter configurations.
