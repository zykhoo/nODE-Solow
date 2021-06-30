# nODE-Solow

All code was run on Julia version 1.4.2

All codes run with the environment set up in model 0. 

# Data:

We collect annual frequency experimental data for various countries from the following sources. All data was publicly available and downloadable. The sources and citations are in the published paper Neural Ordinary Differential Equations for the Regression of Macroeconomics Data under the Green Solow Model. Alternatively, users can use the datafile we have prepared, named `compileddf.csv`:

- Capital data <img src="https://render.githubusercontent.com/render/math?math=k_t"> is sourced from the Penn World Tables, the series is named Capital stock at Current Purchasing Power Parities.
- <img src="https://render.githubusercontent.com/render/math?math=s"> representing the savings rate is from the World Development Index, with a series named Adjusted savings: gross savings (% of GNI).
- <img src="https://render.githubusercontent.com/render/math?math=y_t"> is output per capita at time t (also refered to as GDP or income). We use data from Angus Maddison, which runs from 1960 to 2008.
- Data from Angus Maddison is also used for population growth, <img src="https://render.githubusercontent.com/render/math?math=n">.
- Data for <img src="https://render.githubusercontent.com/render/math?math=\theta"> is from Brock and Taylor, but was originally from the OECD.
- Data for <img src="https://render.githubusercontent.com/render/math?math=e_t"> is from the World Bank
- Data for <img src="https://render.githubusercontent.com/render/math?math=g_A"> and <img src="https://render.githubusercontent.com/render/math?math=g_B"> are from Brock and Taylor. The former is estimated via regression while the latter is estimated as <img src="https://render.githubusercontent.com/render/math?math=n + g_B + \delta=0.05">
