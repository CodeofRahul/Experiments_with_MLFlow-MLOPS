# Experiments_with_MLFlow-MLOPS
This repo has a complete demonstration of performing experiment tracking using mlflow.




## Some useful `env` commands:

- To create environment = `conda create -p <env_name> python=3.8 -y`
- To check available envs = `conda env list`
- To check available envs = `conda info --envs`
- To activate environment = `conda activate <env_name>`
- To install requirements.txt = `pip install -r requirements.txt`
- To check install packages = `pip list`
- To check detailed about package = `pip show package_name`
- To install package = `pip install package_name`
- To uninstall package = `pip uninstall package_name`
- To check install package = `package_name --version`
- To check list of package in venv = `pip freeze --local` or `pip list --local`


## Git commands

- To add all file = `git add .`
- To add any particular file = `git add <file_name>`
- To commit = `git commit -m "commit message"`
- To push the code = `git push origin main`

## Documentation

- mlflow docs : https://mlflow.org/docs/1.25.1/index.html
- mlflow core-concepts : https://mlflow.org/#core-concepts
- Quickstarts : https://mlflow.org/#core-concepts
- mlflow models : https://mlflow.org/docs/1.25.1/models.html
- github : https://github.com/mlflow/mlflow

- For remote server only (Dagshub) : https://dagshub.com/


### if mlflow local tracking "mlflow ui" not working:
- **make sure you have the correct jinja2 and flask**

- Upgrade Flask and Jinja2 to compatible versions:
`pip install --upgrade flask jinja2`

- Alternatively, if you need specific versions due to compatibility:
`pip install flask==2.2.5 jinja2==3.1.2`

- Reinstall MLflow
```
pip uninstall mlflow
pip install mlflow
```

- Now run `mlflow ui` again