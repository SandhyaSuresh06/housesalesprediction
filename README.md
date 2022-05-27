# housesalesprediction

Information on using this project

Development workflows
=======================

Create new project using cookiecutter
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:SandhyaSuresh06/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named housesalesprediction, then do;

```bash
git remote add origin git@github.com:SandhyaSuresh06/housesalesprediction.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── housesalesprediction	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder


Documentation
--------------

This project contains the following files

* aap_hw1_s22_sklearn_Suresh.ipynb is the jupyter notebook containing EDA, model building and evaluation of the housing data
* sweetviz_report.html contains the automated EDA results
* hw1_sklearn_dataprep.ipynb contains the data prep information
* The data files are present in the data folder
* aap_hw1_s22_sklearn.ipynb is the skeleton jupyter notebook





