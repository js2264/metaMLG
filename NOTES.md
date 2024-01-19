## Devtools - `bioconda` env

```shell
mamba create -n bioconda && conda activate bioconda

## python 3.12
mamba install -c conda-forge python=3.12.1

## cookiecutter
mamba install -c conda-forge cookiecutterpip

## Poetry
curl -sSL https://install.python-poetry.org | python3 - 
```

## Kickstart package

```shell
cookiecutter https://github.com/py-pkgs/py-pkgs-cookiecutter.git
# ...
```

## git support

```shell
git init
echo "# metaMLG" > README.md
git add README.md
git commit -m "first commit"
git branch --set-upstream-to=origin/devel
git push 
```

## Create package conda env

```shell
mamba create --name metamlg python=3.12 -y && conda activate metamlg
```
