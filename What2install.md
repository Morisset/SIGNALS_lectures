## What to do to prepare yourself for the lectures:

All the necessary software is installed and ready on the CANFAR server at [https://signals.canfar.net](https://signals.canfar.net). You need to have an account on GitHub and be part of the GitHub signals-sitelle organisation, check this with Laurie. Each participant will have acces to the cloudy program and the needed python libraries from Linux shell and Python 3 notebooks. 

Anyway, if you want to follow the lecture using your own computer, you will need the following:
 
- **Install CLOUDY**. We will use the last version c17.02, available from here: https://www.nublado.org/
- Add the current directory to the search path for Cloudy executable. In your ~/.bashrc or equivalent, add: `export CLOUDY_DATA_PATH="./:+"`
- **Python libraries**: You will need to have the ***numpy, pandas, scipy, matplotlib, h5py,  astropy, atpy, and pymysql*** libraries installed. Most of them are pre-installed for any decent python distribution, but check it before starting the lecture. You will also need PyNeb and pyCloudy. They can be installed from pip: 
   - `pip install pyneb` 
   - `pip install pyCloudy`
- **The notebooks of the lectures**. They will be available from the following repository: https://github.com/Morisset/SIGNALS_lectures. The notebooks are still not on the repository, I will upload them a few hours before the first lecture. 

## Before starting the lecture, on your machine or the Canfar server:

- open a terminal, download the lecture by `git clone https://github.com/Morisset/SIGNALS_lectures.git`
- As I will certainly update the notebooks during the lecture (correcting mistake, making disgretions), the best is to **COPY** the notebooks I'm working with in another place to avoid my updates to delete any of your experiments: `cp -r SIGNALS_lectures/Notebooks/ Notebooks`
- **ALWAYS** open the Notebooks to play with from this Notebooks directory, **NOT** from the SIGNALS_lectures/Notebooks/. 
- From time to time, I will ask you to update the Notebooks by: `cd SIGNALS_lectures; git pull`. This will not change your own Notebooks, so you can still have your own version of them.