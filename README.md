# Yolov5 Dota

this fork has to goal to allow user to train yolov5 on a subset of the dataset DOTA which contain images of 640 by 640 pixel. Thoses images contain 16 classes.

## training
to train the model you must first of install the dependencies:
```
pip install -U -r yolov5/requirements.txt
```

then you can train the model with the line:
```
python3 yolov5_DOTA/train.py --data yolov5_DOTA/data/dota.yaml --weights yolov5s.pt --cfg yolov5_DOTA/models/yolov5s_custom.yaml --epochs 100 --batch 4 --freeze 10

```
