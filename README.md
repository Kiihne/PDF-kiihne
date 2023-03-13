# PDF-kiihne
README for "Fitting Probability Distribution Functions in Turbulent Star-Forming Molecular Clouds"
By Avery Kiihne
3/12/2023

full_write.ipynb - 
  The first script that needs running, this constructs covering grids and saves time later on by making 
it so we can just call the covering grids.

full_pipeline.ipynb - 
  This is the main script for the project. It combines all PDF scripts used in the paper. It includes 
independent fitting, Piecewise fitting, and Spline fitting. It includes the column and volume density 
version of these fitting methods. This script also includes a number of analysis plots used in the paper, including 3D slope
comparision and spline VS piecewise 3D slope. Spline VS piecewise 3D transition density and width of lorgnormal VS time is not used in paper.

3D_slopes.ipynb - 
  This script includes a number of comparision plots, some used in the paper, some not. Piecewise VS spline 2D slopes is used in the paper. 
The rest are not used in the paper.Plots of 3D slopes comparision for piecewise and spline, with all 3 lines of sight shown. 
spline VS piecewise 3D slope with ability to display specific % cases. Piecewise VS spline 2D slopes and Piecewise VS spline 3D slopes.

All other files - 
  Contain earlier versions of code, most of which is encorporated into the 3 main scripts.



