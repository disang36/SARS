
## Model Training

To train our model on `Video` (with default hyper-parameters): 

```
python main.py --dataset=Video --train_dir=default 
```

or on `ml-1m`:

```
python main.py --dataset=ml-1m --train_dir=default --maxlen=200 --dropout_rate=0.2 
``` 
