# conda create/(de)activate env

In order to better use vscode virtual environment, I use conda to manage my environments named myenv (change `myenv` with other name).

First, create an environment 
`conda create --name myenv`,

or to create an environment with a specific version of Python 
`conda create -n myenv python=3.6`,

or to create an environment with a specific version of a package 
`conda create -n myenv scipy=0.15.0`.

Second, activate your env 
`conda activate myenv`,

or deactivate you env when you are under `myenv`:
`conda deactivate`

Third, delete an environment
`conda remove --name myenv --all`

# Other command lines to know

Find all env
`conda env list`




