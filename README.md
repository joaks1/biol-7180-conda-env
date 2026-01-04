This repo contains a YAML-formatted file for setting up a `conda` environment
we will use during our Scripting for Biologists (BIOL 7180) class.

# How to download the environment file

Open your shell terminal and use the following command to clone this git repo:

    git clone


# How to create the conda environment

After cloning the repository, move into the downloaded directory:

    cd biol-7180-conda-env

Then, use `conda` (or `mamba`) to create the environment specfied in the
`conda-env.yml` file:

    conda env create -f conda-env.yml
