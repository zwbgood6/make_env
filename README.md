# virtualenv

From source: https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

Install virtualenv

`python3 -m pip install --user virtualenv`

Create project folder - `MADDPG` (this folder includes `cloned files from github` and `myenv`) 

`cd MADDPG`

Create `myenv` (change `myenv` with other name), 

`python3 -m venv myenv`

`cd myenv/bin`

`source activate`

Deactivate `myenv` when you are under `myenv`:

`deactivate`

**Attention**: Only putting `myenv` in the project folder can vscode finds `myenv`. 

## vscode

Change the env in vscode

`ctrl+shift+P`

Type

`Python: Select interpreter`

Choose `myenv`

____________________________________________________________________________________________________________________________

# conda

From source: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

Different from `virtualenv`, `conda` don't have to put `myenv` in project folder.

Create an environment 

`conda create --name myenv`,

or to create an environment with a specific version of Python 

`conda create -n myenv python=3.6`,

or to create an environment with a specific version of a package 

`conda create -n myenv scipy=0.15.0`.

Activate `myenv`

`conda activate myenv`,

Deactivate `myenv` when you are under `myenv`:

`conda deactivate`

Delete `myenv`

`conda remove --name myenv --all`

Other command lines to know

Find all env

`conda env list`

## vscode

Change the env in vscode

`ctrl+shift+P`

Type

`Python: Select interpreter`

Choose `myenv`


