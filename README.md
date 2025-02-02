# 2025-Rice-datathon

This is our submission for the 2025 Rice Hackathon for the Neurotech track!

We present a machine learning model capable of predicting certain psychiatric disorders given EEG data.

Brain Data -> Machine Learning Model (XGBoost) -> Prediction of Psychiatric Disorder

# Summary of Files

 - main.ipynb - Code for building the model of the project
 - Metrics_MultiClass.ipynb - Code for running the benchmarks for the different datasets
 - Neurotech@Rice Challenge Document 2025 Rice Datathon.pdf - Challenge Document specifying what the outputs should be

INPUTS:
 - Test_Set_EEG.csv - EEG data that DO NOT contain any specific disorders. This is only used to judge the output of the final model
 - Train_and_Validate_EEG.csv - EEG data with main and specific disorders
 - final_dataset_train_all.csv - injected data from referenced github
 - final_dataset_train_all.csv - injected data from referenced github

OUTPUTS:
output.csv


# Team Upper Bound Loss

Kyle Zhang,
Jv Kyle Eclarin,
Damon Spencer


# References

https://github.com/ayushkoirala/Psychiatric-Disorders-Multi-Class-Classification-From-EEG-Data-Using-Machine-Learning-

Park, S. M., Jeong, B., Oh, D. Y., Choi, C., Jung, H. Y., Lee, J., Lee, D., & Choi, J. (2021). Identification of major psychiatric disorders from Resting-State electroencephalography using a machine learning approach. Frontiers in Psychiatry, 12. https://doi.org/10.3389/fpsyt.2021.707581
