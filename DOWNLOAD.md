Dataset **Outdoor Hazard Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI3ODlfT3V0ZG9vciBIYXphcmQgRGV0ZWN0aW9uL291dGRvb3ItaGF6YXJkLWRldGVjdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJhTzZ4Y2dRbFBBZmYrSGtZaUJlbEZtY0lXM3NVSjNnV0swdzRYSlhuU0FzPSJ9)

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