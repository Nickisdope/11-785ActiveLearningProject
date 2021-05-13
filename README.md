# 11-785ActiveLearningProject
# This is the repository of 11-785 course project: 
### Incorporating Active Learning with Self-Training based Abusive Language Detection
# Group Members (Andrew ID): 
* Chuiyu Wang (chuiyuw)
* Yimeng Gu (yimengg)
* Haoyue Zhao (haoyuez)
* Xiang Liu (xliu4)

# 1. Datasets
1. English Datasets:

https://drive.google.com/drive/folders/1NjCtBvOKRjCiVbmEWKmqhHiweW5NdhtH?usp=sharing

2. Turkish Datasets:

https://drive.google.com/drive/folders/1HK_NeTg_PN7iRwl73O9RD8xUVBUhUjda?usp=sharing

# 2. Code Preparation
* Download the English datasets to the ./EnglishDataset/ directory
* Download the Turkish datasets to the ./TurkishDataset/ directory
* Clone the huggingface xlm-roberta repository
* Check if the file of pretrained model parameters is around 1GB, if not, use wget to re-download it (already scripted in a code cell)

# 3. Code Running
* Run the code cell step by step
* If you have already cloned the huggingface xlm-roberta repository, skip the relevant code cell
* The code contans 2 stages: 
### 1. Pretrain the model on English dataset
### 2. Finetune the model on Turkish dataset
