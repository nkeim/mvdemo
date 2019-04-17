# mvdemo
Machine vision demos for PyData SLO

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/nkeim/mvdemo)

If you have conda or Anaconda installed, you can also clone/download this to your own computer, and in this directory run

```
conda create -f environment.yml
conda activate mvdemo
python -m ipykernel install --user --name mvdemo --display-name mvdemo
```

See the `environment.yml` file (and maybe uncomment some lines) if you are interested in installing some optional dependencies to enable more features of trackpy and pims, such as reading movie files.
