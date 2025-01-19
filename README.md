## HI-MGSyn: A Multi-Granularity Network for Predicting Synergistic Drug Combinations

### Model
- Framework
  ![](https://github.com/gracygyx/DSA-DeepFM/blob/master/pictures/framework.jpg)

- Dual-Stage Attention-Enhanced mechanism
  ![](https://github.com/gracygyx/DSA-DeepFM/blob/master/pictures/Attention.jpg)

### Data preparation



- We preprocessed the O'Neil dataset and saved it in npy format,  which can be downloaded from Google drive. 

       https://drive.google.com/drive/folders/1KQU7kKH-MFl2bJhsrLv1ZHxm35Nvhhsf?usp=drive_link
      




- Place the downloaded npy files in the "DSA-DeepFM" directory.

### Environment

```
pip install -r requirements.txt
```


### Train and Test

Our program is easy to train and test,  just need to run "main_DSA_DeepFM_oneil.py". 

```
python main_DSA_DeepFM_oneil.py
```

### Performance on DrugCombDB and O'Neil datasets

- DrugCombDB dataset
  ![](https://github.com/gracygyx/DSA-DeepFM/blob/master/pictures/DrugCombDB.jpg)

- O'Neil dataset
  ![](https://github.com/gracygyx/DSA-DeepFM/blob/master/pictures/oneil.jpg)
