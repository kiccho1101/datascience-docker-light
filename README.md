# datascience-docker-light

## What is this

- Lighter version of [datascience-docker](https://github.com/kiccho1101/datascience-docker)
- DockerHub URL: [https://hub.docker.com/repository/docker/youodf/datascience](https://hub.docker.com/repository/docker/youodf/datascience)

## What you can do with this Docker image

This image includes

### Jupyter environment

- jupyter notebook
- jupyter lab

### Machine Learning libraries

- scikit-learn
- LightGBM
- PyTorch
- Tensorflow
- XGBoost
- CatBoost

### Python linting libraries

- flake8
- isort
- black
- mypy

### Visualizing libraries

- matplotlib
- plotly
- seaborn
- bokeh

## How to build

```bash
docker-compose build
```

## How to use

Pull the docker image from [DockerHub](https://hub.docker.com/repository/docker/youodf/datascience-light)

```bash
docker pull youodf/datascience-light
```

## Run the docker image with command

```bash
docker run youodf/datascience-light COMMAND
```

## Create local environment for python linting

```bash
pipenv install
```

### Example

JupyterLab

```bash
docker run youodf/datascience-light jupyter lab --ip='0.0.0.0' --allow-root --no-browser
```

Jupyter Notebook

```bash
docker run youodf/datascience-light jupyter notebook --ip='0.0.0.0' --allow-root --no-browser
```

Python scripts

```bash
docker run youodf/datascience-light python xxx.py
```
