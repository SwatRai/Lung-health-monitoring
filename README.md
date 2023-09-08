# Lung-health-monitoring

Paper:
Swati Rai, Jignesh S. Bhatt, and Sarat Kumar Patra. (2022). _Accessible, affordable and low-risk lungs health monitoring in covid-19: Deep cascade reconstruction from degraded lr-uldct_. In 2022 IEEE 19th international symposium on biomedical imaging (ISBI) (pp. 1–5). IEEE.

Link:
https://ieeexplore.ieee.org/abstract/document/9761566

We present deep cascade reconstruction of degraded low-resolution ultra-low-dose computed tomography (LR-ULDCT) chest images to restored and super-resolved (SR) ULDCT as accessible, affordable, and relatively less hazardous recourse for lung health monitoring in COVID-19; when compared to relatively less available, costly, and high radiation dose high-resolution CT (HRCT). The degraded LR-ULDCT is first restored with an unsupervised dictionary-based deep residual learning network that handles degradations along with Poisson noise found in CT data. The restored version is given to the SR network which increases its spatial resolution by minimizing adversarial loss between LR-ULDCT and reconstructed SR-ULDCT within the minimax game. It is then fed for segmentation which is achieved by an additional block of convolution, Leaky-ReLU, and batch-normalization in U-Net. Thus restored segmented SR-ULDCT estimates the presence of ground glass opacity and facilitates monitoring of lung health at par HRCT. Comparative experiments and ablation studies are presented using synthetic and real CT data.

The python code for each subnetwork, along with dataset links is provided. 

Some of the sample images used in this research are given below:

![image](https://github.com/SwatRai/Lung-health-monitoring/assets/42530214/010afbe0-2a13-4671-8e6d-b324758fb5a6)
![image](https://github.com/SwatRai/Lung-health-monitoring/assets/42530214/c4803e42-1b80-436b-a5bd-0a6dda5b9d5d)
![image](https://github.com/SwatRai/Lung-health-monitoring/assets/42530214/7296e85d-109d-4974-990b-8717ebfe59bb)
