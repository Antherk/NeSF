# NeSF: Neural Shadow Field for Two-bounce-NLOS Imaging

## Result

### Simulated Scene
We built a simulation test scenario in Blender and conducted brief trainingand reconstruction on several hidden targets. The figure shows our detailed reconstruction results. For more experimental details, please refer to the first part of the supplementary materials.

<img src="image/001.gif" alt="Example Image" width="165px" height="165px" />
<img src="image/002.gif" alt="Example Image" width="165px" height="165px" />
<img src="image/003.gif" alt="Example Image" width="165px" height="165px" />
<img src="image/004.gif" alt="Example Image" width="165px" height="165px" />

### Real-world Scene
We also placed a target in the real test scenario shown in the figure below, and by obtaining the shadow of the wall, we reconstructed the objects in the hidden scene.

<img src="image/real-world scene.jpg" alt="Example Image" width="200px" height="200px" />
<img src="image/real-word data.png" alt="Example Image" width="165px" height="200px" />
<img src="image/real-world reconstruction.gif" alt="Example Image" width="300px" height="200px" />


## Citation
Our experiment was based on a pytorch implementation of NeRF, and the code reference is as follows.
```
@misc{lin2020nerfpytorch,
  title={NeRF-pytorch},
  author={Yen-Chen, Lin},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished={\url{https://github.com/yenchenlin/nerf-pytorch/}},
  year={2020}
}
```