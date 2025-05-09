# FE 620 Pricing Asian Options for US Brent Crude Oil Futures
Authors: Shyam Parikh, Matthew Thomas, Shubh Joshi, and Karen Gong

We researched the aread of Asian Option Pricing. For our experiment, we gathered data from Brent Crude Oil Futures(BZ=F).
To conduct our experiment, we specifically started off with trying to model Asian options using Binomial tree Methods, 
however, that proved to be inefficient. Then, we moved on to implementing Monte-Carlo Methods and validating them through 
methods described in the Vadim Linetsky paper. We did this for both Arithmetically Averaged Options and Geometrically 
Averaged Options.  From there, we worked on hedging analysis using both regular delta hedging for the Arithmetically averaged
Options, and then Dynamic Delta Hedging for the Geometrically Averaged Options.

Key Locations: 
If you go into src, you will find our code, listed as an HTML file, PDF file, and also a Jupyter Notebook. You can view the PDF file
on your browser if you are interested in viewing our code. However,  if you would like to play with out code, feel free to use the
Jupyter Notebook.

Workflow: 
The following information is all not too accurate
Matthew Thomas - Development of the Arithmetic Averaging using Monte Carlo, and moodel validation 
Shyam Parikh - Development of the Geometric Averaging Asian Options using Monte Carlo, and model validation
Karen Gong - Hedging Analysis
Shubh Joshi - Collection and Data Analysis
