Create env

```bash
conda create -n wineq python=3.7 -y
```

create req file

install the req

```bash
pip install -r requirements.txt
```

```bash
git init

dvc init

dvc add data_given/winequality.csv

git add . && git commit -m "first commit"

git remote add origin https://github.com/meAnirban/simple-dvc-demo.git

git branch -M main

git push -u origin main
```

oneliner updates for readme
```bash
git add . && git commit -m "update Readme.md"
```

```bash
dvc repro

dvc metrics show

dvc metrics diff
```

tox command -
```bash
tox
```

for rebuilding -
```bash
tox -r 
```

pytest command
```bash
pytest -v
```

setup commands -
```bash
pip install -e . 
```

build your own package commands-

```bash
python setup.py sdist bdist_wheel
```

find the app -
https://wine-abhowmi-4991.herokuapp.com/
