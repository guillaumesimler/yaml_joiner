# README **YAML Joiner"**

## Important foreword


## Aim of the project

The aim of the project is to **build a small programm to join two yaml files without having package problems** 

It will integrate two yaml or yml files and merge it into one you.

## How to use it

### Install and run the ipython modules

It is quite self explaining when you're used to Anaconda & Jupyter Notebook: 

1. you'll have to install the environment:

	>
	> conda create env -f yaml_joiner.yaml
	>

2. After this, please activate the environment

For Windows:

	>
	> activate yaml_joiner 
	>

3. And run Jupyter Notebook

	>
	> jupyter notebook
	>

4. Then run all cells

### Exchange the target file (copy and paste) and update the environment

1. Activate the environment:

	>
	> activate [target_yaml] 
	>

2. Update the environment:

	>
	> conda env update -f [target_yaml].yaml
	>

### In worst case, remove the environment and reinstall it

1. Remove the environment

	>
	> conda remove --name [target_yaml] --all
	>


2. Reinstall the environment:

	>
	> conda env create -f [target_yaml]
	>

## Used Packages 

An **[Anaconda](https://www.anaconda.com/) environment**, named **yaml_joiner.yaml**, is used to managed packages.



