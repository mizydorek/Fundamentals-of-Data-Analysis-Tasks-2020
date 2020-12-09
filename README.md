![GMIT Logo](http://password.gmit.ie/images/logo.png "GMIT Logos")
# Fundamentals of Data Analysis

Repository for the Tasks assessment for Fundamentals of Data Analysis module @ GMIT - 2020

Author: Maciej Izydorek Email: G00387873@gmit.ie Github: [mizydorek](https://github.com/mizydorek)

#

#### Tasks

*Four tasks will be listed here at different times during the semester. You should complete all tasks in a single jupyter notebook. This, along with relevant files like a README, should be in a single git repository synced with a hosting provider like GitHub [1]. That URL should then be submitted using the link on the Moodle page.*

1. Count function

>*Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A'] should have output {'A': 3, 'B': 1, 'C': 1}. Your code should not depend on any module from the standard library1 or otherwise. You should research the task ﬁrst and include a description with references of your algorithm in the notebook.*

2. Dice rolls

>*Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as diceroll(k=2, n=1000) should return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}*

3. Numpy binomial function

>*The numpy.random.binomial function can be used to simulate ﬂipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is ﬂipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we ﬂip a coin 100 times in a row the chance of getting 50 heads is relatively high,the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates ﬂipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.*

4. Simpson’s paradox

>*Simpson’s paradox is a well-known statistical paradox where a trend evident in anumber of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x, y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.*

#### Contents of repository

The repository contains:

* `README.md` file
* `numpy.random.ipynb` — jupyter notebook contains solution to the assignment
* `requirements.txt` — contains list of packages need to run the notebook
* `.gitignore` — contains list of files that have to be ignore
* `assessment.pdf` — contains the instructions for the Tasks assessment for Machine Learning and Statistics 

#### Required software

The following software is required to run the notebook:

* `git` — open source software to download the repository onto computer[3]
* `python` — Python Programming Language
* `Numpy. Pandas. SciPy. Matplotlib. Seaborn. Jupyter` — python packages used to solve the tasks.[5,6,7,8,9] 

* `Anaconda` — Individual edition of Anaconda can be install to get all of the relevant software.[4]

or alternatively the following command will install the packages according to the configuration file

```
$ pip install -r requirements.txt
```

#### Instructions for downloading repository

At github repository [Fundamentals of Data Analysis](https://github.com/mizydorek/Fundamentals-of-Data-Analysis-Tasks-2020) click on the green `Code` button to copy the link. Open command line(windows) or terminal(osx/linux), navigate to the selected directory and enter the command `git clone` folowed copied the URL. Alternatively copy the whole command below:

```
git clone https://github.com/mizydorek/Fundamentals-of-Data-Analysis-Tasks-2020.git
```

The whole repository will be cloned down onto current working directory.

#### How to run the jupyter notebook

From there run `jupyter notebook` command on the command line/terminal. This will open Jupyter in the browser. The notebook containing solution that is called `numpy.random.ipynb` can be opened by clicking on it.
Once opened, select `Restart and Run All` from Kernel sub-menu to run the jupyter notebook.

#### Viewing the Notebook 

The notebook can be viewed online either on the [github](https://github.com/mizydorek/Fundamentals-of-Data-Analysis-Tasks-2020/blob/main/tasks.ipynb) or by accessing through Jupyter Notebooks viewer  [nbviewer](https://nbviewer.jupyter.org/github.com/mizydorek/Fundamentals-of-Data-Analysis-Tasks-2020/blob/main/tasks.ipynb).

#### References 

[1] Python (https://www.python.org/downloads/) 

[2] Project Jupyter. Jupyter notebook. (http://jupyter.org/)

[3] Software Freedom Conservancy. Git. (https://git-scm.com/)

[4] Anaconda. Individual Edition. (https://www.anaconda.com/products/individual)

[5] NumPy developers. Numpy. (http://www.numpy.org/)

[6] Pandas (https://pandas.pydata.org/)

[7] SciPy (https://www.scipy.org/)

[8] Matplotlib (https://matplotlib.org/)

[9] Seaborn (https://seaborn.pydata.org/)

[10] GMIT. Quality assurance framework. (https://www.gmit.ie/general/quality-assurance-framework)