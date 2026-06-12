# ANDA Day 1: Spike Train Correlations

## Staff

 - **Lead Trainer**: 
   - Nicholas Del Grosso, Uni Bonn, Germany
 - **Lecturers**: 
   - Sonja Grün, Forchungszentrum Jülich, Germany
   - Junji Ito, Forchungszentrum Jülich, Germany
 - **Teaching Assistants**: 
    - Ole Bialas, Uni Bonn, Germany
    - Michael Denker, Forchungszentrum Jülich, Germany
    - Cristiano Köhler, Forchungszentrum Jülich, Germany
    - Tobias Michels, Forchungszentrum Jülich, Germany
    - Julio Rodino, Forchungszentrum Jülich, Germany
 

## Session Overview

How can we tell whether neurons are coordinating their activity, rather than
simply firing at similar rates or responding to the same event?

In this hands-on session, we will explore statistical methods for finding
correlations in neuronal spike trains. We will work with simulated data, where
we know the underlying correlation structure, as well as multi-trial recordings
from macaque motor cortex.

We will begin by visualising and describing spike trains, then use
cross-correlation histograms to look for pairwise relationships. A correlation
peak is not automatically evidence of a meaningful interaction, so we will
compare different surrogate methods and discuss how the choice of null model
affects our conclusions.

Later, we will move beyond pairs of neurons and look at approaches for detecting
synchronous activity and recurring patterns across larger populations. Along
the way, we will experiment with analysis choices such as bin size, time window
and firing-rate stationarity.

The aim is not to treat these methods as black boxes. You will change
parameters, compare results and build an intuition for what each analysis can
and cannot tell us.

## Before the Session

### 1. Clone this Git Repository

`git clone https://github.com/ANDA-NI-2026/ANDA-Day1-Spike-Train-Correlations.git`

### 2. Set up your Python Environment

`pixi run install-kernel`

### 3. Open the Repo in VS Code or Jupyter Lab

For jupyer lab: `pixi run jupyter`. After JupyterLab opens, select the `anda-d1` kernel.

### 4. Complete the Homework

Please complete the exercises in the jupyter notebook in `01_homework`.  

Basic familiarity with Python, NumPy and Matplotlib is enough. We will introduce relevant parts of the neuroscience-specific packages `Neo`, `Elephant`, `quantities` and `Viziphant` throughout the exercises.

### 5. Submit the Homework


Once it's complete (or, at least, you've made a solid attempt to complete at least 75% of it, even if you got stuck), please prefix your last name to the filename (e.g. Homer Simpson would make "`simpson_01_homework.ipynb`") and send it to  the day's dropbox at https://uni-bonn.sciebo.de/s/pLsAYmGW5zLnnHR.



##  Come to the Session!

The rest of the day's materials, including exercise, notebooks, datasets, and solutions will appear in this repo during the session.  Just call `git pull` and you'll get the updates.

See you there!
