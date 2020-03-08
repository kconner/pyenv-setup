Install `pyenv`.

```bash
brew install pyenv
```

Use pyenv to install a version of Python.

```bash
pyenv install --list
pyenv install 3.8.1
```

Specify that this folder should use a certain version of python.

```bash
pyenv local 3.8.1
```

Verify that the setting was saved to disk.

```bash
cat .python-version
pyenv local
```

Run python with the indicated environment.

```bash
pyenv exec python
```

Get instructions for setting the shell python automatically.

```bash
pyenv init
```

In your project folder, verify that your version is used.

```bash
pyenv version
```

In a configured shell, run python with the indicated environment.

```bash
python
```

Install some common packages.

```bash
pip install numpy matplotlib pandas opencv-python
```

