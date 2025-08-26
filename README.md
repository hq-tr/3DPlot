# 3DPlot
A simple Python routine to make a 3D surface plot or heatmap from a .csv file.

Given an input file `input.csv` file with three columns containing the (x,y,z) values, create a heatmap by the following

`./3DPlot -f input.csv`

Instead of a heat map, a surface plot can be created by adding the `-s` tag

`./3DPlot -f input.csv -s`

For surface plots, interpolation options are available. To see them, run the help command:

`./3DPlot -h`
