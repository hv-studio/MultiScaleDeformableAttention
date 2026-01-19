# MultiScaleDeformableAttention 

- github source: https://github.com/fundamentalvision/Deformable-DETR

- Modified:
  
  - MultiScaleDeformableAttention/src/ms_deform_attn.h & MultiScaleDeformableAttention/src/cuda/ms_deform_attn_cuda.cu
    - `*.type().is_cuda()` -> `*.is_cuda()`
    - `*.type()` -> `*.scalar_type()`

- CUDA on the computer should be compatible with the version of CUDA that pytorch is compiled, which means that 11.x, 12.x, 13.x ... are usually incompatible!

- Installation:

  ```shell
  pip install --no-build-isolation -e .
  ```

