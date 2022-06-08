# Pre-Trained Language Models for Interactive Decision-Making

### [Project Page](https://shuangli-project.github.io/Pre-Trained-Language-Models-for-Interactive-Decision-Making/) | [Paper](https://arxiv.org/abs/2202.01771)


This is the official codebase for **Pre-Trained Language Models for Interactive Decision-Making**.


## Setup
### Get the VirtualHome Simulator
Download VirtualHome exectuable file (v2.2.5). Please refer to [VirtualHome](https://github.com/xavierpuigf/virtualhome.git) for more details.

The VirtualHome exectuable file we used can be downloaded from [here](https://www.dropbox.com/s/xxfm38fvttlo34m/virtualhome.zip?dl=0). Put it under `./virtualhome`.


### Download Checkpoints
Download the checkpoint: [LID-Text](https://www.dropbox.com/s/gxk37enz4em2y47/model.pt?dl=0). Put the checkpoint under `./behavior_cloning/checkpoint`.


## Inference

Download Virtualhome initial environment for testing: [data](https://www.dropbox.com/s/d4040dt5g3dxjf0/data.zip?dl=0). Put them under `./data`.

For interactive evaluation, run:
```bash
sh scripts/inference.sh
```


