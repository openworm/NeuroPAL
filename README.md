# NeuroPAL

[![Continuous builds](https://github.com/openworm/NeuroPAL/actions/workflows/omv-ci.yml/badge.svg)](https://github.com/openworm/NeuroPAL/actions/workflows/omv-ci.yml) [![Test Notebooks](https://github.com/openworm/NeuroPAL/actions/workflows/test-notebooks.yml/badge.svg)](https://github.com/openworm/NeuroPAL/actions/workflows/test-notebooks.yml)

This repository contains some test scripts which use the NeuroPAL datasets.

**Note: Work in progress! Subject to change without notice! Please get in contact if you would like to reuse this dataset, to help improve the quality of the conversion**


# Canonical positions and colors

A canonical set of positions for the cell bodes as well as colors reflecting expression levels has been produced. A description of the data can be found in: **Toward a more accurate 3D atlas of <i>C. elegans</i> neurons**, Michael Skuhersky, Tailin Wu, Eviatar Yemini, Amin Nejatbakhsh, Edward Boyden & Max Tegmark [BMC Bioinformatics volume 23, Article number: 195 (2022)](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-022-04738-3)

More details on the data can be found [here](data/CanonicalPositions/README.md), and a Jupyter notebook containing the conversion of this data to NeuroML is [here](TestCanonicalPositions.ipynb).

![Screenshot_Canonical.png](https://raw.githubusercontent.com/openworm/NeuroPAL/main/NeuroML2/Screenshot_Canonical.png)

<p align="center"><i>The above image shows the canonical positions and colors <a href="https://www.opensourcebrain.org/projects/neuropal/repository/revisions/main/show/NeuroML2?explorer=https%253A%252F%252Fraw.githubusercontent.com%252Fopenworm%252FNeuroPAL%252Fmain%252FNeuroML2%252FNeuroPAL_Canonical.net.nml">visualised on Open Source Brain</a>.</i></p>


# Head and tail datasets

The original publication on NeuroPAL was: Eviatar Yemini, Albert Lin, Amin Nejatbakhsh, Erdem Varol, Ruoxi Sun, Gonzalo E. Mena, Aravinthan D.T. Samuel, Liam Paninski, Vivek Venkatachalam, Oliver Hobert, <b>NeuroPAL: A Multicolor Atlas for Whole-Brain Neuronal Identification in <i>C. elegans</i></b>,
[Cell, Volume 184, Issue 1, 2021](https://doi.org/10.1016/j.cell.2020.12.012).

The dataset released with this publication on positions and colors (as used in Figures 2 and 7) of cells in the head and tail has been used in [this Jupyter notebook](TestLoadingData.ipynb), and extracted from the Excel sheet, and converted to NeuroML format.

![Screenshot_HM.png](https://raw.githubusercontent.com/openworm/NeuroPAL/main/NeuroML2/Screenshot_HM.png)

<p align="center"><i>The above image shows the data <a href="https://www.opensourcebrain.org/projects/neuropal/repository/revisions/main/show/NeuroML2?explorer=https%253A%252F%252Fraw.githubusercontent.com%252Fopenworm%252FNeuroPAL%252Fmain%252FNeuroML2%252FNeuroPAL_Herm_Male.net.nml">visualised on Open Source Brain</a>, with the data from the male worm shown in front (head to left, tail to right, shifted to be adjacent), and the equivalent hermaphrodite data behind.</i></p>

# Whole body datasets

Updated data has been provided by Michael Skuhersky on the whole body cell positions and colors. Conversion of this data can be seen [here](TestWholeWorm.ipynb).

![Screenshot_Whole.png](https://raw.githubusercontent.com/openworm/NeuroPAL/main/NeuroML2/Screenshot_Whole.png)

<p align="center"><i>The above image shows the whole worm data <a href="https://www.opensourcebrain.org/projects/neuropal/repository/revisions/main/show/NeuroML2?explorer=https%253A%252F%252Fraw.githubusercontent.com%252Fopenworm%252FNeuroPAL%252Fmain%252FNeuroML2%252FNeuroPAL_All_straightened.net.nml">visualised on Open Source Brain</a>. Seven worm reconstructions are shown, and the worm body/layout has been straightened/standardized as described <a href="https://www.biorxiv.org/content/10.1101/2021.06.09.447813v1.full">here</a>.</i></p>
