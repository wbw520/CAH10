## Usage

##### Data Set
Our dataset is available by contacting bowen.wang@is.ids.osaka-u.ac.jp 
##### Data Samples
![Samples](images/samples.png)

##### Training
Using the following command
```
python main.py ----data_root [your root to place the dataset] --output_dir [root for save the model] --base_model resnet18
```

##### Evaluating
```
python evaluation.py 
```

##### Evaluating
```
python retrieval.py --index [the number to choose the inference sample image]
```

##### UMAP Visualization
```
python umap.py 
```
