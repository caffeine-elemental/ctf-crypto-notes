# Cyberchallenge Workshop

## install and run with venv

Tested in Mint 20

```bash
python3 -m pip install --user --upgrade pip
python3 -m pip install --user --upgrade virtualenv
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade wheel 
python3 -m pip install --upgrade -r requirements.txt
jt -t monokai
jupyter notebook
```

## [Themes](https://github.com/dunovank/jupyter-themes):

onedork | grade3 | oceans16 | chesterish | monokai | solarizedl | solarizedd

```bash
jt -l
jt -t onedork -fs 95 -altp -tfs 11 -nfs 115 -cellw 88% -T
jt -t grade3 -fs 95 -altp -tfs 11 -nfs 115 -cellw 88% -T
```

