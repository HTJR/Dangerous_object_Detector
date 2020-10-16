# Yolov3 custom object detector 
### Use the YOLOv3_Tutorial.ipynb note book in google colab to train your own object detector

```python
net = cv2.dnn.readNet("yolov3.weights", "yolov3.cfg")
```
### Change the name of weights and .cfg file in detector.py with the name of file you are using

### Currently classes.txt contains name of 80 classes in [COCO](https://cocodataset.org/#home) dataset you can change the name to classes of your own choice if you train it on custom dataset

### Use the wieghts and .cfg file that are saved in your google drive after training yolov3 detector

### You can download [Yolov4.weights](https://drive.google.com/file/d/1nbCEW-gG08zakvGkTdL319_RUqTiNFLQ/view?usp=sharing) [Yolov4.cfg](https://drive.google.com/file/d/1ZHokj9JKVBh9kQy98rwFj2lIZDEhjeiO/view?usp=sharing)  that are trained on [COCO](https://cocodataset.org/#home) dataset<br/>

### You can also use [Yolov3.weights](https://drive.google.com/file/d/17sQyTIvcAOtLomNl4ydXOimRx9zBuK4B/view?usp=sharing) [Yolov3.cfg](https://drive.google.com/file/d/1Q9GhXifuAszsCThWOL5FTlWrNUbhhKTn/view?usp=sharing) which is trained on images provided by [dataset](https://github.com/MeioJane/SIXray)<br/>

```bibtex
@INPROCEEDINGS{Miao2019SIXray,
    author = {Miao, Caijing and Xie, Lingxi and Wan, Fang and Su, chi and Liu, Hongye and Jiao, jianbin and Ye, Qixiang },
    title = {SIXray: A Large-scale Security Inspection X-ray Benchmark for Prohibited Item Discovery in Overlapping Images},
    booktitle = {CVPR},
    year = {2019}
}
```

### Uncomment line 103 to save the detected images in folder 
```python
cv2.imwrite(os.path.join(pa , os.path.basename(img_path)) ,img)
```

# Dangerous_object_Detector
![Example 1](examples/main.jpg)<!-- -->
![Example 2](examples/P00017.jpg)<!-- -->
![Example 3](examples/P00946.jpg)<!-- -->
![Example 4](examples/P00959.jpg)<!-- -->

# Detection on coco dataset
![Example 1](examples/000000002923.jpg)<!-- --><br/>
![Example 2](examples/000000026690.jpg)<!-- --><br/>
![Example 3](examples/000000051738.jpg)<!-- --><br/>
![Example 4](examples/000000054164.jpg)<!-- --><br/>
![Example 5](examples/000000118209.jpg)<!-- --><br/>


