# MAGNet
Magnification-Arbitrary Generative Adversarial Network for Image Super-Resolution

# Requirements

* Python 3.10
* Pytorch 2.5.1
* PIL 11.0.0
* numpy 1.26.4
* random
* math
* os
* time
* tqdm


# Installation instruction

1. Download the code

```
git clone https://github.com/gs18050/MAGNet.git
```

2. Upload the project to Google drive.

3. Download the DIV2K dataset from [DIV2K](https://data.vision.ee.ethz.ch/cvl/DIV2K/).

4. Put the training dataset into dataset/train and validation set to dataset/valid.

5. Edit the drive_root in the 4th cell to your own drive path.

6. Run the MAGNet.ipynb code.

# References

1. ESRGAN: https://github.com/xinntao/ESRGAN, https://github.com/XPixelGroup/BasicSR

2. Meta-SR: https://github.com/XuecaiHu/Meta-SR-Pytorch, https://github.com/Lornatang/MetaSR-PyTorch

3. Set5: https://people.rennes.inria.fr/Aline.Roumy/results/SR_BMVC12.html

4. Set14: https://github.com/jbhuang0604/SelfExSR
