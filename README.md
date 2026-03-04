# GFformer

The source code of **GFformer: A Graph Transformer for Extracting All Frequency Information From Large-scale Graphs**


## Training
To reproduce the results of GFformer on the Amazon2M dataset, please run following commands.
```
python test_Amazon2M.py 
```
If you need to apply GFformer to other datasets, simply modify the dataset section and use the hyperparameters suggested in the paper for training.

## Dataset
One can download the Amazon2M dataset from the google drive link below:
https://drive.google.com/drive/folders/1A5m7_wFT6rX7dxEHlKV_uqce5pPVRwnC?usp=sharing. 
Please place the downloaded dataset into the data folder.

## Citing

Please cite our work if you find it is useful for you:
```
@article{
  title = {GFformer: A Graph Transformer for Extracting All Frequency Information from Large-Scale Graphs},
  author = {Zhang, Qi and Si, Mengmeng and Sun, Yanfeng and Wang, Shaofan and Gao, Junbin and Yin, Baocai},
  year = 2025,
  journal = {ACM Transactions on Knowledge Discovery from Data},
  volume = {19},
  number = {8},
  pages = {1--20}
}

```
