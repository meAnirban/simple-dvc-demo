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

dvc repro