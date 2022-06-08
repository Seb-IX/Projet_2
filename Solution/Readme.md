# Requierement :

- pip
- conda

# Notebook viewer 

<a href="https://nbviewer.org/github/Seb-IX/Projet_2/blob/main/Solution/P02_01_notebook.ipynb" target="_blank">Open Notebook_viewer</a>

# Data :

Data use on this project is on "../Ressource/" or <a href = https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/AI+Engineer/Project+2+Participez+%C3%A0+un+concours+sur+la+Smart+City/p2-arbres-fr.csv>on download here</a>.


# Conda environment :

## Why to use
The use of conda allows to virtualize the environment which will be used to use our script. <br>
This use allows to have all the components necessary to the execution of the code since a virutualized environment in to avoid the overload of necessary installation of library.

## How to use :

Create environment : <br>
`conda env create --file environment.yaml` <br>

Activate environment : <br>
`conda activate projet2`<br>

Exit current environment : <br>
`conda deactivate projet2`

To remove environment : <br>
`conda env remove --name projet2` <br>

To create environement file (export current environement to file)  : <br>
`conda env export > environment.yaml` <br>


## Add environment to Jyputer notebook :

This tells jupyter to take the current environment("projet2")<br>
`python -m ipykernel install --user --name=projet2`

