### Upload to  Pypi

```python
%run setup.py sdist bdist_wheel
```

```python
#!pip install --user --upgrade twine
```

```python
# upload the repository to pypi (test)
#!python3 -m twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

```python
# install the repository from pypi (test)
#!python3 -m pip install --index-url https://test.pypi.org/simple/ --no-deps torchkeras
```

```python

```

### Upload to github

```python
#!git init 
```

```python
!git add -A
```

```python
!git commit -m"revise readme"
```

```python
!git remote add origin https://github.com/lyhue1991/torchkeras
```

```python
!git push origin master 
```

```python

```