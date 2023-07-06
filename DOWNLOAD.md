Dataset **Cattle Face** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/H/J/1a/IUgRHxaDmeicWEv4d7xNeFymUl3svXvcMHD9r1A5aiH8hlsGgKIpM80LLL4U3DxRTX1ci6mtrEZXrHeaXUVjUweyK1MER2Wwvu3Nd6Z9TvJzxE3tbjV7b5gL5X73.tar)

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