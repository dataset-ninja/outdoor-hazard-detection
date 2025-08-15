Dataset **Outdoor Hazard Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjc4OV9PdXRkb29yIEhhemFyZCBEZXRlY3Rpb24vb3V0ZG9vci1oYXphcmQtZGV0ZWN0aW9uLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogImt4dW1Xb1p1a2QrY3E4QTJXZ2RBWTVxYWJoTmc2UWUvWXF2MXdDKzVKZ3c9In0=?response-content-disposition=attachment%3B%20filename%3D%22outdoor-hazard-detection-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Outdoor Hazard Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/sukai3316/outdoor-hazard-detection-dataset).