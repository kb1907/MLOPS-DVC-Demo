create environment

```bash
    conda create -n wineq python=3.9 -y
```

activate environment

```bash
    conda activate wineq
```

create requirement file

```bash
    touch requirements.txt
```

install requirements

```bash
    pip install -r requirements.txt
```

create template

```bash
    touch template.py
```

downlaod the data

```bash
git init
```

```bash
dvc init
```
```bash
dvc add data_given/winequality.csv #data-folder/name-of-the-data
```

```bash
git add .
```
```bash
git commit -m "first commit"
```

oneliner updates for readme
```bash
git add . && git commit -m "update Readme.md"
```
