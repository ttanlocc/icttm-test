## 1. Start MinIO

```
docker-compose -f docker-compose.mino.yml up
```

## 2. Virtualenv

- Install micromamba: https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html
- Create mamba environment

```
$ micromamba env create -n icttm python=3.8
```

- Activate environment

```
$ micromamba activate icttm
```


