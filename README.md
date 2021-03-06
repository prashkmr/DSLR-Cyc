<p align="center"><img src='./DSLR/images/cover.png' width="60%"/></p>

# DSLR: Dynamic to Static LiDAR Scan Reconstruction Using Adversarially Trained Autoencoder

[[Project Page]](https://dslrproject.github.io/dslr/)[[AAAI 2021 Conference Paper]](https://arxiv.org/abs/2105.12774)[[Appendix]](https://drive.google.com/file/d/17_O46lNyFqbstTfqN377qX0NMJZAuD1e/view)[[AAAI Presentation]](https://www.youtube.com/watch?v=Mi8DNw6F5Mk&ab_channel=PRASHANTKUMAR)

PyTorch implementation of our supervised image-to-image translation method for Dynamic to Static Reconstruction of LiDAR scans. Our model called DSLR works on range image based LiDAR data and uses an adversarially trained auto encoder via an input pair based discriminator.

Contact: Sabyasachi Sahoo (iamsabyasachisahoo@gmail.com) and Prashant Kumar(email)

## License
Copyright (c) 2021, Prashant Kumar, Sabyasachi Sahoo, Vanshil Shah, Vineetha Kondameedi, Abhinav Jain, Akshaj Verma, Chiranjib Bhattacharyya, Vinay V. All rights reserved under the [GNU General Public License v3.0
](https://choosealicense.com/licenses/gpl-3.0).

## Citation
Please cite our paper if you find the code or dataset useful for your research.

```
@article{DSLR,
  author = {Prashant Kumar, Sabyasachi Sahoo, Vanshil Shah, Vineetha Kondameedi, Abhinav Jain, Akshaj Verma, Chiranjib Bhattacharyya, Vinay V},
  title = {DSLR: Dynamic to Static LiDAR Scan Reconstruction Using Adversarially Trained Autoencoder},
  journal={Association for the Advancement of Artificial Intelligence},
  year={2021}
}
```

## Example Results
<p align="center"><img src='./DSLR/images/output1.png'/></p>
<img src='./DSLR/images/output2.png' width="100%"/>


## Usage
Each folder contains a separate README.md that outlines the environment setup steps and steps for training/testing.
This repository has been divided into the following folders:
 - DSLR : for DSLR and DSLR-UDA models
 - Data : placeholder folder to download the data before training/testing
 - Data_Generation : for Paired Dataset generation algorithm and converting point cloud to range images.
 - LQI : for evaluating static scan reconstruction in absence of ground truth

All the data has been uploaded to kaggle servers. Please refer to "Data" folder for more information.

