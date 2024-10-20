# Toolbox-for-Multi-focus-Image-Stack-Fusion
[Download](https://pan.baidu.com/s/1Njq9uAiRPNiqpZ0Uq3LJAw?pwd=cite)
## For LP,RP,CVT,DWT,DCTWT,NSCT
MST_main_iter_dataset.m
## For DSIFT
Script_iter_datasets.m
## For SwinFusion
iter_swinfusion_datasets.py
## For MFF-GAN
iter_mff_gan_datasets.py
## For SDNet
iter_sdnet_datasets.py
## For U2Fusion
iter_u2fusion_datasets.py

# Help
1. Please make sure that the path in the code points to a parent folder path, under which there are multiple subfolders, each of which contains a set of image stacks consisting of multiple images.
2. If it doesn't work, there may be a problem with the suffix name. Please specify the required image suffix name in the code.
3. All codes have been tested, and StackMFF, IFCNN, and SwinFusion run successfully in the environment of Cuda=11.8. The codes of other methods can be run in the CPU environment.
4. If there are any problems with the code please don't hesitate to ask, we will try our best to solve it

# Cite

If our work is helpful to you, please cite our paper:

@article{xie2024swinmff,
  title={SwinMFF: toward high-fidelity end-to-end multi-focus image fusion via swin transformer-based network},
  author={Xie, Xinzhe and Guo, Buyu and Li, Peiliang and He, Shuangyan and Zhou, Sangjun},
  journal={The Visual Computer},
  pages={1--24},
  year={2024},
  publisher={Springer}
}

@inproceedings{xie2024underwater,
  title={Underwater Three-Dimensional Microscope for Marine Benthic Organism Monitoring},
  author={Xie, Xinzhe and Guo, Buyu and Li, Peiliang and Jiang, Qingyan},
  booktitle={OCEANS 2024-Singapore},
  pages={1--4},
  year={2024},
  organization={IEEE}
}
