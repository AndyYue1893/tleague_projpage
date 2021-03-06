# TLeague Project Page
This is the project page for the following technical reports:

Lei Han∗, Jiechao Xiong∗, Peng Sun∗, Xinghai Sun, Meng Fang, Qingwei Guo, Qiaobo Chen, Tengfei Shi, Hongsheng Yu, Zhengyou Zhang.
TStarBot-X: An Open-Sourced and Comprehensive Study for Efficient League Training in StarCraft II Full Game.
[arXiv preprint arXiv:2011.13729](https://arxiv.org/abs/2011.13729), 2020.
(* Equal contribution, correspondence to the first three authors)

Peng Sun∗, Jiechao Xiong∗, Lei Han∗, Xinghai Sun, Shuxing Li, Jiawei Xu, Meng Fang, Zhengyou Zhang.
TLeague: A Framework for Competitive Self-Play based Distributed Multi-Agent Reinforcement Learning.
[arXiv preprint arXiv:2011.12895](https://arxiv.org/abs/2011.12895), 2020.
(* Equal contribution, correspondence to the first three authors)

<big>**Impatient reader for the StarCraft II AI TStarBot-X could see the [TStarBot-X project page here](tstarbotx/README.md)**<big>.

## Quick Start
* For general TLeague usage, see [the section below](#usage)
* For the resources of TStarBotX, see [the page here](tstarbotx/README.md)
* For the resources of ViZDoom experiments, see [the pager here](vizdoom/README.md)
* For the resources of Pommerman experiments, see [the page here](pommerman/README.md)

## Usage
### Minimal Working Example
To use the TLeague framework and run a minimal training,
one needs to install the following basic packages:
* [TLeague](https://github.com/tencent-ailab/TLeague): the main logic of Competitive SelfPlay MultiAgent Reinforcement Learning.
* [TPolicies](https://github.com/tencent-ailab/TPolicies): a lib for building Neural Net used in RL and IL.
* [Arena](https://github.com/tencent-ailab/Arena): a lib of environments and env-agent interfaces.
See the docs therein for how to install.

Then, try the example of training with the simple game `pong-2p` as a sanity check. 
See the [link here](https://github.com/tencent-ailab/TLeague/blob/dev-open/docs/EXAMPLE_SM.md#pong-2p).

To run training for other environments, extra binaries and/or packages must be installed, as explained in the following.

### StarCraft II Training
When installing the `Arena` package, 
one needs additionally install [TImitate](https://github.com/tencent-ailab/TImitate),
which is a lib for SC2 observation and action, zstat extraction, replay parsing, etc.
See also the [link here](https://github.com/tencent-ailab/Arena#dependencies).

[Here are examples](https://github.com/tencent-ailab/TLeague/blob/dev-open/docs/EXAMPLE_SM.md#starcraft-ii) 
for both Reinforcement Learning (CSP-MARL) and Imitation Learning in a single machine.

TODO: pointer to the Docker Auto Build repo and say it's yet-another guide to installation from scratch.

TODO: texts for how to train with k8s

### ViZDoom Training
When installing the `Arena` package, 
one needs additionally install ViZDoom (>=1.1.8), 
see the [link here](https://github.com/tencent-ailab/Arena#dependencies).

[Here are examples](https://github.com/tencent-ailab/TLeague/blob/dev-open/docs/EXAMPLE_SM.md#vizdoom)
of how to train ViZDoom in a single machine.

TODO: pointer to the Docker Auto Build repo and say it's yet-another guide to installation from scratch.

TODO: texts for how to train with k8s

### Pommerman Training
When installing the `Arena` package, 
one needs additionally install Pommerman, 
see the [link here](https://github.com/tencent-ailab/Arena#dependencies).

[Here are examples](https://github.com/tencent-ailab/TLeague/blob/dev-open/docs/EXAMPLE_SM.md#pommerman)
for how to train Pommerman in a single machine. 

TODO: pointer to the Docker Auto Build repo and say it's yet-another guide to installation from scratch.

TODO: texts for how to train with k8s

# Disclaimer
This is not an officially supported Tencent product.
The code and data in this repository are for research purpose only. 
No representation or warranty whatsoever, expressed or implied, is made as to its accuracy, reliability or completeness. 
We assume no liability and are not responsible for any misuse or damage caused by the code and data. 
Your use of the code and data are subject to applicable laws and your use of them is at your own risk.