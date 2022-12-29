# Object detection

Implementation of object detection methods:

- [RetinaNet](https://arxiv.org/abs/1708.02002).

They are trained on PASCAL VOC 2012, which can be found [here](https://pjreddie.com/projects/pascal-voc-dataset-mirror/).

The notebooks uses json annotations and therefore the xml-files needs to be converted to json-format. This can be done with xml2json.py, i.e.

```bash
python src/xml2json.py ./data/VOCdevkit 2012
```