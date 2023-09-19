[![Python application](https://github.com/guardiansofpipelines/CA3/actions/workflows/python-app.yml/badge.svg)](https://github.com/guardiansofpipelines/CA3/actions/workflows/python-app.yml)
[![Docker Image CI](https://github.com/guardiansofpipelines/CA3/actions/workflows/docker-image.yml/badge.svg)](https://github.com/guardiansofpipelines/CA3/actions/workflows/docker-image.yml)
# CA3

## For Windows
### create a virtual environment
```bash
python -m venv venv_name
```
### set execution policy
```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```
### activate the virtual environment
```bash
source venv_name/Scripts/activate
```
### Create requirements.txt 
```bash
touch requirements.txt
```
### Add the following to requirements.txt
```
black
pytest
```
### run makefile
```bash
make install
```
### run tests
```bash
make test
```
### run lint
```bash
make lint
```
