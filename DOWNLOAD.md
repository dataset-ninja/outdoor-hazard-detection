Dataset **Outdoor Hazard Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/0/GP/EmtRwk9BMwIm6qjS42ScPPBZ23An4DIQ1S21OFkAdFoWEvUE1qGhraLx9Op6VJwxDGvgTD3J2npwAB1MAAgUW0cmn4pYM4FVFJ8VYfTb1oqjjEcbPKpBVzLIJcBb.tar)

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