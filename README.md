# Recommender Class Project 1 

## Software requirements 
 1. Anaconda 3.8
 2. Git bash

## Starting up project locally 
 1. Create a folder on your local machine where you want stash this project. Open this folder and right click in it. From scroll menu select Git Bash here. 
After application opens insert this line:

<pre>git clone https://github.com/ant3k96/recommender_class_project1</pre>

2. Prepare your conda environment (instructions given for Windows, but it should be similar on other systems):

	1. Open Anaconda Prompt as administrator.

	2. Make sure you're in the repository main folder. Run the following command:
			
		conda env create --name rs-proj-env -f environment.yml

3. Activate just created environment with the following command:

		conda activate rs-proj-env	

4. Then type:

		jupyter notebook

	A new tab with Jupyter Notebook should open in your browser.

5. In Jupyter Notebook open projec1_data_preparation.ipynb.

6. In tab menu select "Cell" and hit "Run all". Wait for the process to finish and close project_data_preparation.ipynb

7. In Jupyter Notebook open project1_recommender_and_evaluation.ipynb 

8. In tab menu select "Cell" and hit "Run all". Wait for the process to finish. 
   <i> NOTE: project is not finished so some errors will be displayed</i>

