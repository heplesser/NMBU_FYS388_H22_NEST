# NMBU_FYS388_H22

Material for the introduction to network modeling with NEST in
FYS388/FYS488 at NMBU in the Fall Term 2022.

## Using these notebooks

These notebooks require NEST 3.3. You can run NEST in several ways.

### Running on EBRAINS

1. If you do not have an EBRAINS account yet, request one at
   https://www.ebrains.eu/register/.
1. Log into https://wiki.ebrains.eu, choose "Collabs" and then "Create
   a collab"; a "private" collab is fine.
1. On the left, choose "Lab"
    - then either "Fenix CH" or "Fenix DE", 
    - then the "Official EBRAINS Docker Image 22.07"
1. In the left margin, click the Git logo
    - click "Clone a repository"
	- enter https://github.com/heplesser/NMBU_FYS388_H22_NEST.git 
	- you will now have a `NMBU_FYS388_H22_NEST` folder in your `My Library`
1. Enter the `NMBU_FYS388_H22_NEST` folder
    - open the `FYS388_H22_NEST_By_Example.ipynb` notebook
	- in the top right corner of the notebook, choose the `EBRAINS 22.07` kernel
1. Any changes you make to the notebook will be stored in the Collab
   Drive
1. If you want to push changes to a Git repo, choose `Git > Add remote repository` 
   to add a repo that you can push to.
   
### Running on Linux

Install NEST as described here:
https://nest-simulator.readthedocs.io/en/v3.3/installation/index.html

### Running on macOS

The easiest approach is to use Conda. The NEST documentation on that
is currently outdated. Proceed as follows:

1. If you haven't installed Conda yet, install Miniconda for your type
   of Mac (Intel/Apple CPU) from
   https://docs.conda.io/en/latest/miniconda.html. 
2. Create an environment with NEST and Conda by running
    ```
    conda create -n nest -c conda-forge nest-simulator jupyterlab
    ```
3. Get the files for the course either with
    ```
    git clone https://github.com/heplesser/NMBU_FYS388_H22_NEST.git 
    ```
	or download  them from Canvas.
4. Start `jupyter lab` in a directory containing the downloaded
   material.
   
### Running on Windows

NEST is not supported under Windows at present. Your best option is to
run NEST on EBRAINS. 

If you have Windows Subsystem for Linux (WSL2) fully installed, you
can try to install Docker (www.docker.com) and then follow the Docker
instructions for Linux/macOS on
https://nest-simulator.readthedocs.io/en/v3.3/installation/index.html 

Otherwise, you can install VirtualBox (https://www.virtualbox.org),
download the [NEST Live
Media](https://nest-simulator.readthedocs.io/en/v3.3/download.html#download-the-nest-image-for-vms)
and [install
it](https://nest-simulator.readthedocs.io/en/v3.3/installation/livemedia.html#nest-live-media-installation).
