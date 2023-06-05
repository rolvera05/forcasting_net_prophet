# *Forcasting Net Prophet*
This project revolves around a Jupyter notebook where I've prepared, analyzed, and visualized MercadoLibre's time-series data. The goal is to determine if there's a correlation between search traffic prediction and successful stock trading.

Inside the notebook, you'll find an exploration of MercadoLibre's Google Search traffic, revealing seasonal patterns. The notebook also evaluates the relationship between MercadoLibre's stock price and its search traffic, seeking potential insights into their financial performance.

A key part of this assignment is the implementation of a Prophet model to predict hourly user search traffic. The notebook includes responses to various question prompts related to the analysis.


---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, hvplot, prophet, pathlib, pystan, holoviews, datetime, %matplotlib inline

- **Framework:** JupyterLab
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

**First things first:**
If you don't have Python, JupyterLab, or Anaconda installed on your operating system:

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

With the Anaconda package installed, you should already have all the necessary libraries to run the main application downloaded except for pystan, prophet, holoviews, and hvplot.


**1. Conda 'dev' Environment** - To run the main application you will need to create a new enviornment that will be compatible with this application, type and enter the following. You will still use the previous steps' command to activate:

        conda create -n env_name python=3.7 anaconda

Activate conda enviorment by running the following function:

        conda activate env_name 
Make sure your enviorment is on created in the correct file and is activated and de-activated once finished.

**2. Other Libraries** - It was mentioned earlier that the other required libraries should already be installed with the Anaconda package. To confirm installation for these libraries, you can either use the 'conda list' command followed by the library name to confirm installation. Or, you can install the libraries which will either install successfully or if already installed, will result in a 'requirement already satisfied' message. Listed below are the commands to install each library if needed:
        
        pip install pystan
        pip install hvplot
        pip install holoviews
        pip install prophet


**3. Clone Repo** - Once you have checked off all previous installation steps, its now time to clone/download this repository onto your local machine for use. To do that, first copy the SSH keys.

Now, in your terminal cd to a location where you want this repo folder to reside. Once you are in your preferred current directory, enter the following:

        git clone 'ssh keys here'

To run the repo folder in JupyterLab for usage, simply cd to the repo folder, then type and enter:

        jupyter lab

### **IMPORTANT:** The Prophet library can occasionally pose installation challenges on certain systems, so for this project, we utilize Google Colab. This cloud-based IDE enables you to execute Jupyter Notebooks remotely. To work with the content from this repository, follow these steps once you have cloned it to your local machine:

1. Open your preferred web browser (Chrome is highly recommended). Enter `https://colab.research.google.com/` in the address bar and hit Enter.

2. After the page has loaded, navigate to 'File' in the top-left corner and click on 'Open Notebook'.

3. A new window will open. Select 'Upload', then click on 'Choose File'. 

By following these instructions, you'll be able to access the notebook contained in this repository through Google Colab, bypassing any potential installation difficulties with Prophet.

---

## *Usage*

### 1. User Input
---

1. **Run the Code**: After you've uploaded your data, you can begin executing your code. Each code cell can be run individually by clicking the 'play' button on the left side of the cell. Alternatively, you can use the shortcut 'Shift+Enter' to run the current cell and advance to the next one.

2. **Read Uploaded Files**: With your file uploaded, you can access it directly using its name in your Python scripts. For example, if your file is named `data.csv`, you can use the following snippet to load it into a pandas DataFrame: 
```python
import pandas as pd 
df = pd.read_csv('data.csv')
```

3. **Save Your Notebook**: It's essential to frequently save your work, especially since Google Colab sessions can timeout after a period of inactivity. Navigate to 'File' > 'Save' to save your progress. Alternatively, you can click 'File' > 'Save a copy in Drive' to create a copy of the notebook in your Google Drive.

4. **Download the Notebook**: If you want to keep a local copy of your notebook, you can download it by going to 'File' > 'Download .ipynb'. If you prefer a Python script version of your code, choose 'File' > 'Download .py'.
Once JupyterLab is open with the repo code, the first thing you will do is open the user_input.ipynb notebook. 

---

## *Contributors*

For any questions, comments, concerns, feel free to contact below: 

**Rosalinda Olvera Fernandez**

[GitHub](https://github.com/rolvera05) - rolvera98271@gmail.com