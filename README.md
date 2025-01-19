## HI-MGSyn: A Multi-Granularity Network for Predicting Synergistic Drug Combinations

### Model
- Framework
  ![](https://github.com/gracygyx/HI-MGSyn/tree/main/Figures/Framework.png)

- Interaction-aware attention mechanism
  ![](https://github.com/gracygyx/HI-MGSyn/tree/main/Figures/Attention.png)

### Environment

```
pip install -r requirements.txt
```


### Train and Test

Our program is easy to train and test,  just need to run "main_DrugComb.py" for DrugComb dataset and  "main_GDSC2.py" for GDSC^2 dataset. 

```
python main_DrugComb.py
python main_GDSC2.py
```

### Performance on DrugCombDB and O'Neil datasets

- DrugComb dataset
  ![](https://github.com/gracygyx/HI-MGSyn/tree/main/Figures/DrugComb.png)

- GDSC^2 dataset
  ![](https://github.com/gracygyx/HI-MGSyn/tree/main/Figures/GDSC2_result.png)
