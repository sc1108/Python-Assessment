Californian Sea Otter Health Project

This project investigates the differences and health of two sea otter populations, one from a highly impacted site (Monterey Bay (MON)) and one not affected by development or many anthropogenic pressures (Big Sur (BSR)). The data was taken from the physical exam of sea otter captures from 2008-2011 which included sex, age class, grizzle subclass, weight, length, girth, tail length, category of nose wound, paw width, tooth wear, canine width and probably of pregnancy. The aim of this python code is to explore how health and morphometric variables varied between region and sex, identify any correlations between variables, identify which variables have the greatest explanatory power to predict sex or regional population and to use those variables to predict a sea otter's sex or regional population.

To run:
1.	Download the sea otter data and notebook available in this repository.
2.	Ensure to change Line 4 to where you have saved the data.
3.	The first part of the code gives a general overview of the data, including histograms, a variable correlation heatmap and distribution plots for sex and region. Before giving individual blow plots for sex and region for each variable.
4.	The second part completes PCA models for both sex and region. Notably, variables which were missing multiple data points were excluded (nose wounds, canine width and grizzle). This section also includes how to plot these models, how to calculate the explained variance of each principal component and identify which variable contributes the most to this variation.
5.	The third and last part of the code completes classification models for sex and region, letting the user input a specific Weight and Length (on line 64 and 76 respectively) for it to predict which sex or region the sea otter is from and plotting the models as boundary graphs.
