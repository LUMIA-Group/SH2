**S**elf-**H**ighlighted **H**esitation (SH2)
![image](framework.jpg)
===
Code for the paper [SH2: Self-Highlighted Hesitation Helps You Decode More Truthfully](https://arxiv.org/abs/2401.05930)

## Environment setup

```
pip install -e transformers
pip install datasets
pip install accelerate
pip install openai # -> only for truthfulqa and gpt4_eval
```

## Example experiments
```
cd experiments # running scripts
```

- **SH2**
```
bash factor_keys.sh # prepare key tokens
bash factor_hard.sh
```

- Baseline: LLaMA_7B, LLaMA2_7B or Mistral-7B-v0.1
```
bash factor_baseline.sh
```

- DoLa (Repo: https://github.com/voidism/DoLa)
```
bash factor_dola.sh
```

## Citation
If you find this work helpful, please cite our paper:
```
@misc{kai2024sh2selfhighlightedhesitationhelps,
      title={SH2: Self-Highlighted Hesitation Helps You Decode More Truthfully}, 
      author={Jushi Kai and Tianhang Zhang and Hai Hu and Zhouhan Lin},
      year={2024},
      eprint={2401.05930},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2401.05930}, 
}
```
