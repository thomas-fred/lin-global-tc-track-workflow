# Lin TC model workflow

This repository encodes workflow to produce tropical cyclone (TC) tracks across
the TC belt, calibrate their annual frequency to observed values and output the
tracks in tabular format for further processing.

## Setup

Clone this repository:
```shell
git clone git@github.com:thomas-fred/lin-global-tc-track-workflow.git
```

Create a conda environment to install the necessary dependencies for track model and parser:
```shell
micromamba create -f environment.yaml
```

Clone Jonathan Lin's tropical cyclone model so it's inside this directory as `model/`.
```shell
git clone git@github.com:linjonathan/tropical_cyclone_risk.git model
cd model
git checkout 171c54b
```

Activate the environment:
```shell
micromamba activate lin-tc-model
```
