## Faster R-CNN课程作业

### 环境依赖
执行 `pip install -r requirements.txt`

### 训练模型

将如下两个预训练模型下载至`./backbone`目录下：

https://download.pytorch.org/models/resnet50-0676ba61.pth（请重命名为"resnet50.pth"）

https://download.pytorch.org/models/fasterrcnn_resnet50_fpn_coco-258fb6c6.pth (请重命名为“fasterrcnn_resnet50_fpn_coco.pth”)

训练只需执行 `python train.py`

最终的模型权重默认放置在`./save_weights`目录下。

### 验证模型精度
执行 `python eval.py`

