## Install

```
sh tools/download_checkpoints.sh
```

## Env

Use plightning build

change mmcv-full version to 1.4.0

## Model Checkpoint

需要从Segformer获取到model

https://github.com/NVlabs/SegFormer

onedrive下载后拖进来

```
unzip pretrained_models.zip
mv 
```

## Download GTA

```
mkdir ./data
ln -s $UDATADIR/GTA5 ./data/gta
ln -s $UDATADIR/Cityscapes ./data/cityscapes

```

## Change worker num

现在

# RUN

```
# Training
python run_experiments.py --config configs/daformer/gta2cs_uda_warm_fdthings_rcs_croppl_a999_daformer_mitb5_s0.py
```
