# SHP-Source-code
Modified program to simulate E.coli population dynamics and include the effect of switching between two subpopulations
SHP CODE USER GUIDE:
The folder NewCode contains all necessary files to run the simulation. New files created for this project to model the switching system include:

•	test.m (blackboxmodel used for Hill fn switching)
•	plot_DGinMapSR.m (plots the heatmap phase diagrams of D against Gin for switching system)
•	plot_SRMap.m (plots the phase diagrams of switching rate parameter space)
•	HillDGinMap.m (creates heatmaps for Hill fn switching rates)
•	DGinPlotsSR.m (plots the protein productivity and yield plots seen in the report)

And files modified include:
•	main.m (main code, from which other plotting files are called)
•	Model.m (blackboxmodel used for the constant switching rates)
•	parameters_values.m (defines all of the model parameters)
•	dynamics.m (file to plot the time evolution of the system)
•	create_heatmapparam.m (defines the size of the D and Gin increments to be simulated over)

Important: test.m should be used when modelling the system with Hill function switching rates, while Model.m used for the constant switching rates.

The 1x289 data structure sr.m is also included in the zip file, as well as the code to create the 3d surface plots: surfaceplotscode.m 
![image](https://user-images.githubusercontent.com/74822457/113325427-5208cb80-9310-11eb-8e7f-66ecb628d3f7.png)
