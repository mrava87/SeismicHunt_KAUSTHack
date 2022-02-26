# SeismicHunt

This repository contains the material used by the SeismicHunt project in the First **KAUST Hackathon in Geoscience**!


### Project description:

The Earth is filled with an invaluable amount of resources that power our daily lives. Natural gas, for example, is going to play a key role in the energy transition as its use is required to produce blue hydrogen. Nevertheless finding such resources is hard and geoscientists play a constant treasure hunt when interpreting seismic data. We wish therefore to devise an artificially intelligent tool that provided with a large set of unlabeled seismic pre-stack data and a small labeled dataset can detect residual gas accumulation in the subsurface (and possibly their shape and saturation).


### Notebooks:

The following notebooks are provided:

`SeismicHunt_gettingstarted`: display the training and testing datasets (requires data to be stored locally;

`SeismicHunt_gettingstarted_colab`: same but in case you are using Colab;



### Accessing data:


SeismicHunt: data for KAUST ML Hackathon 2022


### Environment creation:

When working on your local machine, we suggest to have installed Anaconda or Miniconda on your computer. If you are not familiar with it, we suggesting using the [KAUST Miniconda Install recipe](https://github.com/kaust-rccl/ibex-miniconda-install). This has been tested both on macOS and Unix operative systems. Once this is installed, create a new environment using the `environment.yml` file proved here by simply typing on terminal:

```
conda env create -f environment.yml
```

Note that this file is meant to be a file for template environment, feel free to include other libraries that you will be using!