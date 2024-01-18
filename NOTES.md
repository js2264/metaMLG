## Devtools

```shell
mm create -n bioconda && mm activate bioconda

## python 3.12
mm install -c conda-forge python=3.12.1

## cookiecutter
mm install -c conda-forge cookiecutterpip

## Poetry
curl -sSL https://install.python-poetry.org | python3 - 
```

## Kickstarting package

```shell
cookiecutter https://github.com/py-pkgs/py-pkgs-cookiecutter.git

```


## git support

```shell
git init
echo "# metaMLG" > README.md
git add README.md
git commit -m "first commit"
git branch --set-upstream-to=origin/devel

```
