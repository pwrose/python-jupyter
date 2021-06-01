# Introduction to Python in Jupyter Lab

This repository is a tutorial how to setup Jupyter Lab for Python tutorials.

To setup Python 3 and Jupyter Lab follow these steps.

## 1. Download Miniconda
Click on the latest version (Python 3.9) for your operating system (e.g., Miniconda3 Windows 64-bit) to download the installer.
<p align="center">
<img src="images/miniconda.png", width="60%">
</p>

## 2. Install Miniconda3
Run the Miniconda3 installer (shown here is the installer for Windows 10) by following these steps.
<p align="center">
<img src="images/download.png", width="60%">
</p>

Click Next.
<p align="center">
<img src="images/setup1.png", width="60%">
</p>
Click I Agree.
<p align="center">
<img src="images/setup2.png", width="60%">
</p>
Click Next.
<p align="center">
<img src="images/setup3.png", width="60%">
</p>
Click Next.
<p align="center">
<img src="images/setup4.png", width="60%">
</p>

**IMPORTANT**, select the option "Add Miniconda 3 to my PATH environment Variable" and click "Install"
<p align="center">
<img src="images/setup5.png", width="60%">
</p>
Click Next.
<p align="center">
<img src="images/setup6.png", width="60%">
</p>
</p>

Finally, click finish to complete the installation of Miniconda3.
<p align="center">
<img src="images/setup7.png", width="60%">
</p>

## 4. Open a Command Window/Terminal Window

#### On Window 10

Type "cmd" in the Windows search bar to open a command window.
<p align="center">
<img src="images/cmd.png", width="60%">
</p>

#### On Mac OS

Type "terminal" in the Spotlight Search in top menu bar to open a terminal window.
<p align="center">
<img src="images/terminal.png", width="60%">
</p>

## 5. Install Jupyter Lab using Conda

Type the following command into the command window to install Jupyter Lab.

```conda install -c conda-forge jupyterlab```

 Type "y" to proceed when prompted to complete the installation.

<p align="center">
<img src="images/jupyterlab_install.png", width="60%">
</p>

## 6. Install Pandas using Conda

Type the following command into the command window to install Pandas. 

```conda install -c conda-forge pandas```

Type "y" to proceed when prompted to complete the installation.

<p align="center">
<img src="images/pandas_install.png", width="60%">
</p>

## 7. Create a Directory for the Python Tutorials

Type the following command into the command window to create a new directory.

```mkdir tutorial```
<p align="center">
<img src="images/mkdir_tutorial.png", width="60%">
</p>

## 8. Run Jupyter Lab

Type the following commands to run Jupyter Lab in the tutorial directory.
```
cd tutorial
jupyter lab

```
<p align="center">
<img src="images/tutorial_jupyterlab.png", width="60%">
</p>

Jupyter Lab will launch in your default web browser.
<p align="center">
<img src="images/jupyterlab_launched.png", width="60%">
</p>

## 9. Create a new Notebook 
Select "New -> Notebook" from the File menu.
<p align="center">
<img src="images/new_notebook.png", width="60%">
</p>

Select "Python 3" as the Kernel.
<p align="center">
<img src="images/select_python3.png", width="60%">
</p>

Select "Rename" from the file menu and rename the notebook: ```tutorial1.ipynb```.

## 10. Run a simple Python command in the Notebook
Type ```print('Hello World')``` in the first notebook cell.
<p align="center">
<img src="images/cell_hello_world.png", width="60%">
</p>

Click the run (>) button to execute your first Python command. Make sure the cell you want run is selected. This command will print the text ```Hello World```.

<p align="center">
<img src="images/run_hello_world.png", width="60%">
</p>

Lets add a couple of numbers and print the results. In the second cell, type:
```
x = 5
y = 7
z = x + y
print(z)
```
and click the run (>) button again to see the result.
<p align="center">
<img src="images/run_add.png", width="60%">
</p>

Congratulations, you've run your first Python code in a Jupyter Lab.

Select "Shutdown" from the File menu when you are finshed with your first tutorial.
<p align="center">
<img src="images/shutdown.png", width="60%">
</p>

To start Jupyter Lab again, go to step 8, create new notebooks and follow the same steps.

Now you are ready to learn Python!







