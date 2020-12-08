# pytorch-fixes

**Platform**

- CPU: 2 x Intel(R) Xeon(R) CPU E5-2695 v4
- GPU: NVIDIA Tesla V100 16GB

**Fixes**

- SpatialConvolutionMM

Tests: *1-spatial-convolution-model.py* (1.05x), *1-spatial-convolution-unit.py* (1.16x)

https://github.com/pytorch/pytorch/issues/48539
 
- ReplicationPad

Tests: *2-replication-pad3d.py* (1.15x)

https://github.com/pytorch/pytorch/issues/48889

