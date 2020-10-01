# vscode-python-venv

Easily set up python virtual environments for development in [vscode](https://github.com/microsoft/vscode).

## Example

```bash
cd <somewhere>
git clone git@github.com:ruestefa/vscode-python-venv.git
cd vscode-python-venv
python -V  # e.g., 3.8.3
python -m venv venvs/3.8.3
./venvs/3.8.3/bin/python -m pip install -U pip
./venvs/3.8.3/bin/python -m pip install -r requirements/python.txt
```

Then, in vscode, select `<somewhere>/vscode-python-venv/venvs/3.8.3/bin/python` as the python interpretor.

