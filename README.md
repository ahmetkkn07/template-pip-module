## Python Pip Module Template

Change all ```<module-name>``` to your projetc name.
### Update To PyPI.org

```
pip install --upgrade setuptools wheel tqdm
pip install twine
rm -rf build/ dist/
python setup.py sdist bdist_wheel
twine upload dist/*
```
