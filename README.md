# Paper plots

This repository contains the scripts to reproduce the plots made in the original paper describing the [JUNE](https://github.com/IDAS-Durham/JUNE) model published in [Royal Society Open Science](https://royalsocietypublishing.org/doi/full/10.1098/rsos.210506).

Please cite our paper as follows:

```
@article{doi:10.1098/rsos.210506,
  author = {Aylett-Bullock, Joseph  and Cuesta-Lazaro, Carolina  and Quera-Bofarull, Arnau  and Icaza-Lizaola, Miguel  and Sedgewick, Aidan  and Truong, Henry  and Curran, Aoife  and Elliott, Edward  and Caulfield, Tristan  and Fong, Kevin  and Vernon, Ian  and Williams, Julian  and Bower, Richard  and Krauss, Frank },
  title = {J<span class="smallcaps smallerCapital">une</span>: open-source individual-based epidemiology simulation},
  journal = {Royal Society Open Science},
  volume = {8},
  number = {7},
  pages = {210506},
  year = {2021},
  doi = {10.1098/rsos.210506},
  URL = {https://royalsocietypublishing.org/doi/abs/10.1098/rsos.210506},
  eprint = {https://royalsocietypublishing.org/doi/pdf/10.1098/rsos.210506},
}

```

## Running

These plots require version 1.0.5 of the [JUNE](https://github.com/IDAS-Durham/JUNE) framework to be installed:

```
pip install -r requirements.txt
```

and the relevant data downloaded:

```
get_june_data.sh
```

Next, a 'world' must be created: see [example script](https://github.com/IDAS-Durham/JUNE/blob/master/example_scripts/create_world.py).

All plots can be plotted using the `master_plotter.py` script:

```
python june_plots/scripts/master_plotter.py -w [PATH TO WORLD FILE]
```