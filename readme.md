# GCS

## Environments supported:

- [Multiagent Particle-World Environments (MPEs)](https://github.com/openai/multiagent-particle-envs)
- Collaborative Gaussian Squeeze
- [Google Research Football](https://github.com/google-research/football)


##  Installation

``` Bash
# create conda environment
conda create -n marl python==3.6.1
conda activate marl
pip install torch==1.5.1+cu101 torchvision==0.6.1+cu101 -f https://download.pytorch.org/whl/torch_stable.html
```

```
# install onpolicy package
cd GCS
pip install -e .
pip install -r requirements.txt
```

## Training
Here we use train_mpe.py as an example:
```
cd onpolicy/scripts/train
python train_mpe.py
```
