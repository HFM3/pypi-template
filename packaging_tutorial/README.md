# Example Package
Tutorial on Python packaging: <https://packaging.python.org/tutorials/packaging-projects/>

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.


```console
python3 setup.py sdist bdist_wheel
```

```console
python3 -m twine upload --repository testpypi dist/*
```

```console
python3 -m pip install --index-url https://test.pypi.org/simple/ --no-deps example-pkg-HFM3
```

```console
python3 -m pip install --index-url https://test.pypi.org/simple/ --no-deps example-pkg-HFM3
```

```console
python3
```

```python
import example_pkg
```
