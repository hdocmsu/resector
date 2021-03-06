# `resector`

<p align="center">
    <img src="https://raw.githubusercontent.com/fepegar/resector/master/docs/images/60_examples_resized_50.gif"
        alt="Resections">
</p>

Implementation of a [TorchIO](https://torchio.readthedocs.io/) transform
used to simulate a resection cavity from a T1-weighted brain MRI and a
corresponding[GIF brain parcellation (version 3.0)](http://niftyweb.cs.ucl.ac.uk/program.php?p=GIF).

Accepted at the
Medical Image Computing and Computer Assisted Intervention (MICCAI) 2020 conference:

[F. Pérez-García, R. Rodionov, A. Alim-Marvasti, R. Sparks, J. S. Duncan and
S. Ourselin. *Simulation of Brain Resection for Cavity Segmentation Using
Self-Supervised and Semi-Supervised Learning*](https://arxiv.org/abs/2006.15693).

## Installation

```shell
$ git clone https://github.com/fepegar/resector.git
$ pip install --editable ./resector
```

## Usage

```shell
$ resect t1.nii.gz gif_parcellation.nii.gz t1_resected.nii.gz t1_resection_label.nii.gz
```

Run `resect --help` for more options.
