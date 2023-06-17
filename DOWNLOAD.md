Dataset **Cattle Face** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/E/I/ZT/ab7jPoMQSTEEHKC33FVM9LGOlIdf4tyCY4yo1qjoOjFlgOpUODiUaDHto7Tmib2lJPmX7Kn3NtFDrftQ1UC8q9atnTghSuUzRmnqRwn3Ecb61yO7huCyLcNYrCK3.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Cattle Face', dst_path='~/dtools/datasets/Cattle Face.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/kstate-kdd/cattle-face-dataset/dataset/2/download)