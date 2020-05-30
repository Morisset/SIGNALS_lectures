## What to do to prepare yourself for the lectures:

Everything will be available on the Canfar server. You need to have an account on it, check this with ???. Each participant will have acces to the cloudy program and the needed python libraries from Linux shell and Python 3 notebooks. 

Anyway, if you want to follow the lecture using your own computer, you will need the following:
 
- **Install CLOUDY**. We will use the last version c17.02, available from here: https://www.nublado.org/
- Add the current directory to the search path for Cloudy executable. In your ~/.bashrc or equivalent, add: `export CLOUDY_DATA_PATH="./:+"`
- **Python libraries**: You will need to have the ***numpy, pandas, scipy, matplotlib, h5py,  astropy, atpy, and pymysql*** libraries installed. Most of them are pre-installed for any decent python distribution, but check it before starting the lecture. You will also need PyNeb and pyCloudy. They can be installed from pip: 
   - `pip install pyneb` 
   - `pip install pyCloudy`
- **The notebooks of the lectures**. They will be available from the following repository: https://github.com/Morisset/SIGNALS_lectures **which is closed for now** and will be open the day before the first lecture. I will certainly update the notebooks during the lecture, so the best is to clone the repository (`git clone https://github.com/Morisset/SIGNALS_lectures.git`) and to **COPY** the notebook I'm working with, when starting each session, in another place to avoid my updates to delete any of your experiments. 
