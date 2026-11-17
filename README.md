# ASAG-Source-Material
1. The Training Code: Model name, dataset and hyperparameter details can directly be edited to switch among selected alternaives.
2. On Google Colab, save the trained model with the classifier to your mounted drive using the following commands:
3. !zip -r file_name.zip /content/model_name_seed
4. !cp -r /content/model_name_seed /content/drive/MyDrive/
5. We have provided 5 Models Fine-Tuned on SciEntsBank dataset. Instead of training from scratch, paths to our fine-tuned models can be directly mentioned in the Testing code.
6. Testing Code: It loads the perturbation datasets, models and trained classifiers.
The code tests macro f1 drops, class-wise judgement transitions and association beteween judgement retention/ transition and representation displacement.
7. Perturbations: SciEntsBank test perturbations have been provided in this repository introducing noise: orthographic errors and paraphrastic alterations. The sets were labelled for meaning preservation after perturbing student answers.
8. File and Model names ending with 01 refer to files and models related to RTE training paradigm, while the same ending with 02 refers to resources related to RCC paradigm.
