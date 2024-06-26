# Apptainer4Pconda

This is an example of multi-stage build of an apptainer container for a Conda environment 
based on stuff provided by Jupyter team (originally Docker stuff).
All stuff strictly based on conda install also will install within the resulting image.
You need to provide a local `.cache` directory binding for `/home/jovyan/.cache`.
