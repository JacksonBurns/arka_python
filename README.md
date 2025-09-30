# arka_python

Python implementation and demo of Banerjee and Roy's ARKA method

## Installing

I installed these versions of packages, using `python==3.10.*`:

```
numpy>=2
rdkit
scikit-learn
mordredcommunity
pandas
ipykernel
```

The actual implementation of the ARKA method uses a narrow subset of the `numpy` API which should be compatible with basically all versions of Python 3.x.
For this exact demo, I used the `mordred` descriptors with `mordredcommunity` which supports Python 3.8 or newer.

To access the demo data you will also have to install `polaris` (Polaris via `polaris-lib` on PyPI) and `PyTDC` (Theraputic Data Commons), but you don't need that to run the code otherwise.
These packages can't be installed in the same environment because of dependency conflicts (or maybe they can, I'm just too lazy to wait for `pip` to resolve the install), so you will need two separate environments.

## Running

See [`arka_carbonmangels.ipynb`](./arka_carbonmangels.ipynb).
