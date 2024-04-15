# EECS 592 WN24 Team 4 Project
## Data Pre-processing
A. Start from init.
1. Download [MIMIC-IV dataset](https://physionet.org/content/mimiciv/2.2/)
2. Decompress files to folder `pipeline/mimiciv/` 
3. Run `pipeline/mainPipeline.ipynb`
4. Run `pipeline/process.ipynb`
5. Run `pipeline/clean.ipynb`

B. Download pre-processed files (created by running the steps above)
1. Download `cleaned.tar.gz` on [Google Drive](https://drive.google.com/file/d/159aKhGxyXE5ZYltZ432my_DigVejN4B6/view?usp=drive_link)
2. Decompress files to folder `pipeline/cleaned/`

## Model Training and Evaluation
Run `train.ipynb`  
Change model setup and hyperparameters in the notebook   
Trained models will be saved at `models/`
