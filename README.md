Install pyenv

```bash
brew install pyenv
```

Use pyenv to install a version of Python

```bash
pyenv install --list
pyenv install 3.8.1 # for instance
```

Specify that this folder should use a certain version of python

```bash
pyenv local 3.8.1
```

Verify that the setting was saved to disk

```bash
cat .python-version
pyenv local
```

Run python with chosen environment.

```bash
pyenv exec python
```

