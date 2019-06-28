# rmm_min_reproduce

To compile, run the below command
```console
nvcc -O3 -std=c++11 -o minReproduce  minReproduce.cu -I<path-to-rmm-headers> -lrmm -gencode arch=compute_52,code=sm_52 -gencode arch=compute_70,code=sm_70
```
