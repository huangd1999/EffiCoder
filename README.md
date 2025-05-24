# EffiCoder: Enhancing Code Generation in Large Language Models through Efficiency-Aware Fine-tuning

## Installation

```bash
cd EffiCoder
pip install -r requirements.txt
cd LLaMA-Factory
pip install -e ".[torch,metrics]"
```

## Fine-tune LLMs with EffiCoder

We have provided the EffiCoder dataset in EffiCoder/LLaMA-Factory/data/efficoder.json, so we can directly use SFT and other methods to finetune LLMs.

```bash
cd EffiCoder/LLaMA-Factory
bash run.sh
```

## VLLM inference 

```bash
cd EffiCoder/scripts
bash run.sh
```

## Report Efficiency and pass@1 results

```bash
cd EffiCoder/src
python code_efficiency_calculator.py
python calculate_memory_usage.py
```
