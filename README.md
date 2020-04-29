# DocuSeg - An Open-Source GAN for Document Analysis

![Sample Segmentation](/plots_pix2pix/plot_449800.png)

This repo provides two open-source GANs (Pix2Pix and CycleGAN) that have been trained on IBM's open-source document dataset (PubLayNet)

Models are saved every ten epochs with the name being `model_{step_num}.h5` where `{step_num}` is the step at which the model is saved. Both Pix2Pix and CycleGAN were trained for 100 epochs.

## Important Links
- [Original Pix2Pix Model](https://phillipi.github.io/pix2pix/)
- [Original CycleGAN Model](https://junyanz.github.io/CycleGAN/)
- [PubLayNet Dataset](https://github.com/ibm-aur-nlp/PubLayNet)

