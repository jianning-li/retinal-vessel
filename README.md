#V-GAN #
### Retinal Vessel Segmentation in Fundoscopic Images with Generative Adversarial Networks ###

![bitbucket_header.jpg](https://bitbucket.org/repo/ekyjKAX/images/3167681377-bitbucket_header.jpg)

## Directory Hierarchy ##
```
├── codes
│   ├── evaluation.py
│   ├── inference.py
│   ├── model.py
│   ├── train.py
│   ├── utils.py
├── data
│   ├── DRIVE
│   └── STARE
├── evaluation
│   ├── DRIVE
│   └── STARE
├── inference_outputs
│   ├── DRIVE
│   └── STARE
├── pretrained
│   ├── DRIVE_best.h5
│   ├── DRIVE_best.json
│   ├── STARE_best.h5
│   ├── STARE_best.json
│   ├── auc_pr_STARE.npy
│   ├── auc_roc_DRIVE.npy
│   ├── auc_roc_STARE.npy
│   └── auc_roc_pr_DRIVE.npy
└── results
    ├── DRIVE
    └── STARE
```

## Training ##
Move to codes and run train.py
``` python train.py --ratio_gan2seg=<int> --gpu_index=<int> --batch_size=<int> --dataset=[DRIVE|STARE] --discriminator=[pixel|patch1|patch2|image]```


## Inference ##

## Evaluation ##