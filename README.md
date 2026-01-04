This repo contains a YAML-formatted file for setting up a `conda` environment
we will use during our Scripting for Biologists (BIOL 7180) class.


# How to download the environment file

Open your shell terminal and use the following command to clone this git repo:

    git clone https://github.com/joaks1/biol-7180-conda-env.git


# How to create the conda environment

After cloning the repository, move into the downloaded directory:

    cd biol-7180-conda-env

Then, use `conda` (or `mamba`) to create the environment specfied in the
`conda-env.yml` file:

    conda env create -f conda-env.yml


# How to use the conda environment

To use the conda environment, use `conda` to activate it:

    conda activate biol-7180


# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/deed.en_US">Creative Commons Attribution 4.0 International License</a>.
