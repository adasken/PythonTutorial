So this course uses the Python programming language throughout it. So the first thing we need to do is make sure you have a Python development environment set up on your personal computer. So we will walk through installing a package called Anaconda which has both the development environment and all the Python packages you need pre-installed. It makes life really easy.

## Anaconda Distributition by Continuum Analytics

1. Go to the website:
https://www.anaconda.com/download/

2. Download the installer (Python 3.6 version) for your OS

3. Run the installer

## Using Anaconda

If you want to install a new package into your Anaconda, type:

```
conda install <package>
```

## Run Jupyter

The Jupyter Notebook App can be launched by clicking on the Jupyter Notebook icon installed by Anaconda in the start menu (Windows) or by typing in a terminal (cmd on Windows):

```
jupyter notebook
```

This will launch a new browser window (or a new tab) showing the Notebook Dashboard, a sort of control panel that allows (among other things) to select which notebook to open. 

When started, the Jupyter Notebook App can access only files within its start-up folder (including any sub-folder). If you store the notebook documents in a subfolder of your user folder no configuration is necessary. So make sure you go to the folder you want (using `cd <folder>` in terminal) before starting Jupyter (`jupyter notebook`).

For more configurations, see: http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html

## Create a Jupyter notebook

1. In the Notebook Dashboard, select **New** &rightarrow; **Notebooks** &rightarrow; **Python 3**.

2. Click on the new notebook file. It will open the Jupyter Notebook App.

3. In the notebook cell, type:
```python
print("Hello World")
```

4. Run cell, press: <kbd>CTRL</kbd>+<kbd>ENTER</kbd>

5. Run cell and insert next, press: <kbd>ALT</kbd>+<kbd>ENTER</kbd>

6. Run cell and select next, press: <kbd>SHIFT</kbd>+<kbd>ENTER</kbd>

7. Remember to save your notebook when done (although it will automatically do the save for your every 3 mins): <kbd>CTRL</kbd>+<kbd>S</kbd>

## Export Jupyter notebook and run it as a Python script

There are two ways to run the Python code in Jupyter notebook as a program:

1. Select **File** &rightarrow; **Download as** &rightarrow; **Python(.py)**

2. On the command line, type:
```
jupyter nbconvert --to script <NOTEBOOK_NAME>.ipynb
```
3. Run the script:
```
python <NOTEBOOK_NAME>.py
```
