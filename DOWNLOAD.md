Dataset **OD-WeaponDetection: Pistol Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4MDdfT0QtV2VhcG9uRGV0ZWN0aW9uOiBQaXN0b2wgQ2xhc3NpZmljYXRpb24vb2Qtd2VhcG9uZGV0ZWN0aW9uOi1waXN0b2wtY2xhc3NpZmljYXRpb24tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAicS9ROGxGUGZmUzh2YkI1MkpQTzkzSG1Kei9sQlZPN1N2Uit6T01BU3JnQT0ifQ==)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='OD-WeaponDetection: Pistol Classification', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://drive.google.com/file/d/1Szc920DAh5kU8Qk38Doq0znEVR1QmTZS/view?usp=sharing).