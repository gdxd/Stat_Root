# Stat_Root

Example notebooks for 
* basic statistic distributions
* ROOT usage
* Random numbers


In order to use it at [LMU jupyterhub](https://jupyter.physik.uni-muenchen.de) you have to do following setup (in terminal/shell) once:
```
module load root/6.32.02
jupyter kernelspec install --user $ROOTSYS/etc/notebook/kernels/root
echo "module load root/6.32.02" > ~/jupyterhub_environment.sh
```

Then select environment  `python/3.11-2023.09 ` when you start on **jupyterhub**
