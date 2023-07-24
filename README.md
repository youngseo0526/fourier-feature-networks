# fourier-feature-networks
This code reproduction of Fourier Feature Network framework in PyTorch implementation

Original [paper](https://arxiv.org/pdf/2006.10739.pdf) and [code](https://github.com/tancik/fourier-feature-networks) were provided

This is my review of [paper](https://breezy-perfume-dec.notion.site/Fourier-Features-Let-Networks-Learn-High-Frequency-Functions-in-Low-Dimensional-Domains-7aa0f1f162b849fb941c678384734752?pvs=4) 


Excute ```demo.ipynb``` in the folder

<p align=center><img src = https://bmild.github.io/fourfeat/img/teaser.png ></p>

## Version Info
```pytorch=1.17.1```
```cudatoolkit=11.6```

## Dataset
[DIV2K_valid_HR](https://data.vision.ee.ethz.ch/cvl/DIV2K/) was used as used in original paper<br>
download file [here](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_HR.zip) and push the file

## Result
| source | PSNR | SSIM |
| ------ | ------| ------|
| paper | 17.125 | 0.713 |
| this repo | 34.634 | 0.982 |

## Reference
[Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains](https://arxiv.org/pdf/2006.10739.pdf)<br>
[Pytorch Fourier Feature Networks](https://github.com/ndahlquist/pytorch-fourier-feature-networks)
 
