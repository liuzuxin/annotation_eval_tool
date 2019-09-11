# annotation_eval_tool

Evaluation code for smart-annotation tool

## Dependencies
```
[bbox](https://pypi.org/project/bbox/), pip install bbox
numpy, json, re, pandas, matplotlib
```

## Preparation
Organize the annotation results and this repo as follows: 
```
annotation_eval_tool
├── eval.ipynb
├── output-annotation
│   ├── 001_val_sync
│   ├── ├── Akhil.0020000000.json
│   ├── ├── Akhil.0020000001.json
│   ├── ├── Akhil.0020000002.json
│   ├── ├── ...
│   ├── 002_val_sync
│   ├── 003_val_sync
│   ├── ...
├── baseline-annotation
│   ├── 001_val_sync
│   ├── ├── 0020000000.json
│   ├── ├── 0020000001.json
│   ├── ├── 0020000002.json
│   ├── ├── ...
│   ├── 002_val_sync
│   ├── 003_val_sync
│   ├── ...
├── kitti_label
│   ├── 0000.txt
│   ├── 0001.txt
│   ├── ...
```
