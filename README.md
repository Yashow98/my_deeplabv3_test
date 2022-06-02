# my_deeplabv3_test
## 预训练权重下载地址：

* 注意：官方提供的预训练权重是在COCO上预训练得到的，训练时只针对和PASCAL VOC相同的类别进行了训练，所以类别数是21(包括背景)
* deeplabv3_resnet50: https://download.pytorch.org/models/deeplabv3_resnet50_coco-cd0a2569.pth
* deeplabv3_resnet101: https://download.pytorch.org/models/deeplabv3_resnet101_coco-586e9e4e.pth
* deeplabv3_mobilenetv3_large_coco: https://download.pytorch.org/models/deeplabv3_mobilenet_v3_large-fc3c493d.pth
* 注意，下载的预训练权重记得要重命名，比如在train.py中读取的是```deeplabv3_resnet50_coco.pth```文件，
  不是```deeplabv3_resnet50_coco-cd0a2569.pth```
