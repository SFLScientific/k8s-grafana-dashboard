# SFL Scientific Project Template

![](imgs/logo.png)

### Purpose


### Project Contents

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── run.sh             <- Bash script to run main function. Main function includes training, inference and QA testing.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling. Data pipeline output data should be saved in this folder.
    │   └── raw            <- The original, immutable data dump. Raw input data should be saved in this folder
    │
    ├── docs               <- Presentations and reports.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks
    │   └── [Prod]<YOUR-NOTEBOOK>.md        <- Your data science NoteBook
    │
    ├── src                <- Source code for use in this project.
    │   │
    │   ├── train.py             <- Train program main script: your training pipeline should go into this script.
    │   ├── predict.py           <- Inference program main function: your inference pipeline should go into this script.
    │   │
    │   ├── datasets           <- Scripts to download or generate data: your dataset related code should go into this folder.
    │   │   └── dataset1.py: Script for data IO and processing
    │   │   └── dataset2.py: Script for data IO and processing
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── builder.py: Script for Model builder. Your model initialization code should go into this script.
    │   │   └── model.py: Script for your model structure. Your model structure code should go into this script.
    │   │   └── trainer.py: Script for model training. Your model training logic should go into this script.
    │   │
    │   ├── preprocesses           <- Scripts to process XXX data
    │   │   └── process.py: data preprocessing main object: update it when you works your own SFL project.
    │   │   └── transform.py: Transforms used in the image preprocessing pipeline: update it when you works your own SFL project.
    │   ├── postprocesses           <- Scripts to process XXX data
    │   │   └── process.py: data postprocessing main object: update it when you works your own SFL project.
    │   │   └── transform.py: Transforms used in the image postprocessing pipeline: update it when you works your own SFL project.
    │   ├── validation           <- Scripts to validate
    │   │   └── validate1.py: fill me
    │   │   └── validate2.py: fill me
    │   ├── netty           <- netty helper functions: includes commonly-used visualization and data split functions.
    ├── tests                <- scrips for QA/QC tests.
    │   │
    │   ├── test_train.py: integration test for your training pipeline: update it when you works your own SFL project.
    │   ├── test_predict.py: integration test for your inference pipeline: update it when you works your own SFL project.
    │   │
    │   ├── datasets           <- Unite test for your dataset objects: update it when you works your own SFL project.
    │   │   └── test_dataset1.py: Script for data IO and processing
    │   │   └── test_dataset2.py: Script for data IO and processing
    │   │
    │   ├── models         <-  Unite test for your builder/model/trainer objects: update it when you works your own SFL project.
    │   │   ├── test_builder.py: Model builder
    │   │   └── test_model.py: Script for your model structure.
    │   │   └── test_trainer.py: Script for model training.
    │   │
    │   ├── processes           <- Unite test for your data pipeline objects: update it when you works your own SFL project.
    │   │   └── test_preprocess.py: data preprocessing main object
    │   │   └── test_transform.py: Transforms used in the image preprocessing pipeline
    │   ├── validation           <- Unite test for your validation pipeline objects: update it when you works your own SFL project.
    │   │   └── test_validate1.py: fill me
    │   │   └── test_validate2.py: fill me

### Notes

(filled out when end-to-end testing commences)

### Known Issues

(filled out when end-to-end testing commences)

### Contacts (tagged list)
    - Developers
    - SFL Scientific founders (Mike, Mike, Dan)