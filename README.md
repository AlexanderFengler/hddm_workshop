# hddm_workshop
Material for a basic **HDDM Tutorial Workshop**. Click [here](https://github.com/hddm-devs/hddm) for more information about the **HDDM** python package, including extensive [documentation](https://hddm.readthedocs.io/en/latest/).


The **code-examples** for the workshop are in the `workshop_main.ipynb` *notebook*.
Included in the presentation are a few **depictions of graphical models**, the source code for which sits in 
the `workshop_daft_models.ipynb` *notebook*.
The **presentation material** is in the `workshop_presentation.ppt` file.

## Installation: Google Colab (recommended)

To run the tutorial in a **google colab**, simply click on this [link](https://colab.research.google.com/github/AlexanderFengler/hddm_workshop/blob/main/workshop_main.ipynb).

Running the first code block in the *notebook*, will prepare the *colab environment* to run the tutorial.

## Installation: Local

Below some basic installation instructions to run this tutorial on local. 
If you instead want to run this tutorial on a **google colab** machine, you find the corresponding installation commands inside the `workshop_daft_models.ipynb` *notebook* itself.

```
# Make your conda environment
conda create --name hddm_workshop python=3.7
conda activate hddm_workshop

# Install prerequisite python packages to execute the tutorial
pip install cython
pip install matplotlib
pip install pymc # if there are problems --> usually here
pip install git+https://github.com/hddm-devs/kabuki
pip install git+https://github.com/hddm-devs/hddm
pip install torch torchvision torchaudio # optional


# Install packages to render the graphical models
pip install daft
```

