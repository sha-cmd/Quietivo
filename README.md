# Quietivo

## Machine Learning Examples

### Installation

To make run this examples on your computer :

- Download and dezip the source code in a directory, type in a terminal:

```shell
$git clone git@github.com:sha-cmd/Quietivo.git
```

- Create a virtual environment with the command

```shell
$cd Quietivo/
$python3.9 -m venv .venv
```
- Launch the virtual environment (on Linux)

```shell
$source .venv/bin/activate
```
on Windows 

```shell
$.venv/bin/activate.bat
```

- Upgrade pip

```shell
$pip install --upgrade pip
```

- Install requirements in the virtual environment

```shell
$pip install -r requirements.txt
```

- You can build a kernel for Jupyter

```bash
$python3 -m ipykernel install --user --name venv --display-name "Quietivo"
```

- You can list kernels :

```shell
$jupyter kernelspec list
```
or delete a kernel

```shell
$jupyter kernelspec uninstall Quietivo
```

- Check that the right jupyter program is launch :

(on Linux)

```shell
$which jupyter
```

(on Windows)

```shell
$where jupyter
```

The return may be ```[Absolute_PATH]/Quietivo/.venv/bin/jupyter```. In other situation, simply modify the path environment variable to make it refering to the right jupyter path of this project.

- Then launch jupyter and choose the kernel Quietivo

```shell
jupyter notebook
```
