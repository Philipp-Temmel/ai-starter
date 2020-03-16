# README

# Description
The goal of this project is to have a starting point (i.e. template project) for any AI projects to avoid redundant project setup work and introduce consistency. This readMe is structured as suggested in the official README.md guideline. The same structure may be used for any project specific instructions. 

# Usage

## Create conda environment from existing yaml

Please use conda and "environment.yaml" to create/modify Python based development environments
for AI projects and manage dependencies.

1) modify first line of "environment.yaml" to your required environment-name

2) modify last line of "environment.yaml" to the directory the environment lives in

3) execute command: `conda env create -f environment.yaml`

environment.yaml
contains a sequence of packages and versions (without sub-dependencies) you need to install 
to obtain a ready-to-use AI environment

## Export existing conda environment in new yaml

Export your environment to a new file: `conda env export --from-history > environment.yaml`

# License
All libraries used in this project are free to use or fall into the BSD-licence are may therefore be commercially used without further restrictions other than keeping the original copyright intact.













