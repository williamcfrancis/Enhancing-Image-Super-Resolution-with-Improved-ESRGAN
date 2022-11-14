# Improved ESRGAN for Image Super Resolution

Image Super-Resolution refers to the conversion of a low-resolution image to a high-resolution image. In this
project, the implementation of ESRGAN is chosen as the baseline to generate a super-resolved image. Multiple experiments
are then performed to improve upon the results from the baseline and also improve the stability of the GAN while training. It
is found that when the baseline is modified to have a different set of losses and other normalizations to stabilize the training,
the perceptual quality increases.

## Test
#### Dependencies
- Python 3
- Install the dependencies in requirements.txt

### Test models
1. Clone this github repo.
```
git clone https://github.com/williamcfrancis/Super-Resolution-with-Improved-ESRGAN.git
cd Super-Resolution-with-Improved-ESRGAN
```
2. Place your own **low-resolution images** in `./LR` folder.
3. Pretrained model weights are present in './weights' folder
4. Run validate.
```
python validate.py
```
5. The results are in `./results` folder.

