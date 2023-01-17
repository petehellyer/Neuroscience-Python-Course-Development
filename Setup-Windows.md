# Installing software on a Windows

## Step 1: Install Python (Anaconda)

1. Download and install Anaconda from https://repo.anaconda.com/archive/Anaconda3-2022.10-Windows-x86_64.exe

## Step 2: Install Git
1. Download and install Git from https://git-scm.com/download/win. Git will ask you lots of questions, Whilst installing, select all the default options. 


## Step 3: Install Jupyter Notebook
1. Now that you have pip, we can use that to install jupyter notebook. This is the place where will write and execute all the Python code. We chose this as it provides a very nice interface and it is easy to use if you are a beginner.
2. Open a terminal by selecting the `Anaconda Prompt (anaconda3)` app from the Windows Menu
2. Once the terminal (or command line) is open, write `pip install jupyter` and press `Enter`
3. To Open `Jupyter` simply type `jupyter notebook` and `Enter`, in `Command Line`
4. To create a new Notebook, click on New (upper right side of the screen) and select Python3 (ipykernel). You can now use this to write your own code. Type `print('Hello World')` and click the `Run` button. If you don't get any errors it means you are all set up and ready to go.
5. to install the packages you need, you have to write the following commands in one cell (or chunk of code) of the jupyer:

    `%%cmd`
    
    `pip install numpy pandas matplotlib`
  

## Step 4: Open the Lecture Materials
1. Open a terminal by selecting the `Anaconda Prompt (anaconda3)` app from the Windows Menu
2. Copy the following commands and press  `Enter ` at the end of each command

     `cd %USERPROFILE%`

     `cd Desktop/`

     `git clone https://github.com/petehellyer/Neuroscience-Python-Course-Development.git`

     `cd Neuroscience-Python-Course-Development`
3. Once it is done downloading, type `jupyter notebook` and `Enter`. This should open a Jupyter interface.
4. If everything worked well, you should now be able to see and open the programming materials we created. To do so, press on the file called `Lecture1.ipnb` and start with the lectures.


## Extra resources

If you have never used Jupyter Notebook before, it might be useful going through this tutorial. This will teach you about its functionalities, and it will be of great help as you progress through the course.

https://www.dataquest.io/blog/jupyter-notebook-tutorial/


If you have any installation issue, write an email to peter.hellyer@kcl.ac.uk
