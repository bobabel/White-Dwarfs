# White-Dwarfs
White dwarf candidates, culled from the Montreal White Dwarf Database and the Fusillo et al. 2021 tables at Warwick University are merged with SDSS and Gaia observations to produce color-magnitude plots for DA, DB and DC white dwarfs (**acquire_WDs.inpynb**). The three input data sets are large and not added to Github, but the output (**MontWarWDs.csv**) is.<br><br> These data input to **model_WDs.ipynb**, where they are then binned by color and the median values are used to create polynomial fits to the data, creating C-M models in each of four SDSS colors (u-g, g-r, r-i and i-z) over the 8.5 ≤ �� ≤ 14.5 range . The output file is **WD.csv**<br><br>
**model_WDMDs.ipynb**  and **MSandRGBcolors_v1.3.txt** (from Ivezič) combines the white dwarf models with M dwarf tables from Ivezič to produce white dwarf/M dwarf binary system models (**WDMD.csv**).<br><br>
**WDs.csv** and **WDMD.csv** are the files we're interested in. The tables are explored in **WD_amd_WDMD_plots.csv**.



