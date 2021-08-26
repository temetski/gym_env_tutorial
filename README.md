## Prerequisites

You need to install OpenAI gym and stable-baselines.
Because stable-baselines only supports `tensorflow` versions 1.8 to 1.15, we must install python 3.7.
```
conda create -n deeprl python=3.7
conda activate deeprl
pip install gym stable-baselines tensorflow==1.15
conda install jupyter
```

## Example
Open the `tutorial.ipynb` notebook.

## References
1. [Custom Cartpole](https://github.com/ray-project/ray/blob/a8813675f4a57706470c79e29ce254325c9ed75c/rllib/examples/env/stateless_cartpole.py)
2. [OpenAI gym Cartpole](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py)
3. [Stable-baselines](https://stable-baselines.readthedocs.io/)
4. [Policy Networks](https://stable-baselines.readthedocs.io/en/master/modules/policies.html)