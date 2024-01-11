# Data processing

## Description
The file ``LCPS_data.zip`` contains the data shared in [Google Drive](https://drive.google.com/drive/folders/1tniAxbA7bkm09Hu1xkpWA81OxHpcfRd3?usp=sharing) in zipped format. Unzip the file and put the extracted contents in this directory. Here, the folder ``LCPS_data`` contains the extracted content.

## Installation

The code is written in Python3.6 and the experiments were run on a machine using Ubuntu 18.04.3 LTS. You can follow the commands below for setting up your project.

### Setting up virtual environment
Assuming you have Python3, set up a virtual environment following the instructions mentioned in the ``README.md`` file.

### Data pre-processing
The code to pre-process the data is provided in the file ``preprocess.ipynb``. Run it to generate `geojson` files of the LCPS data for the school year 2017-18. If everything goes correctly, you should get two files like ``SPAs_2017_2018.json`` and ``Schools_2017_2018.json`` in the folder ``LCPS_data``.
 
Further work will be done using these two data files.
