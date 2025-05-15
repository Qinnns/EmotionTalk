# MERTools



## Environment

```shell
conda env create -f environment.yml
```

- If raise errors about "OSError: libtorch_cuda_cpp.so: cannot open shared object file: No such file or directory", please run "pip install -U torch torchaudio --no-cache-dir"
- If your Cuda version is low (such as 10.2), please check the install instructions for pytorch-relate packages in "https://pytorch.org/get-started/previous-versions"




## MERBench

[**MERBench: A Unified Evaluation Benchmark for Multimodal Emotion Recognition**](https://arxiv.org/pdf/2401.03429)<br>
Zheng Lian, Licai Sun, Yong Ren, Hao Gu, Haiyang Sun, Lan Chen, Bin Liu, Jianhua Tao<br>

Please cite our paper if you find our work useful for your research:

```tex
@article{lian2023mer,
  title={MERBench: A Unified Evaluation Benchmark for Multimodal Emotion Recognition},
  author={Lian, Zheng and Sun, Licai and Ren, Yong and Gu, Hao and Sun, Haiyang and Chen, Lan and Liu, Bin and Tao, Jianhua},
  journal={arXiv:2401.03429},
  year={2024}
}
```
