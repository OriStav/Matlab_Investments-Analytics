Stocks Analysis

Summary:
Plots comparative histograms and graphs which describe thestocks performance over history, and the revenues for the chosen time parameters.

Description:
Steps:
	1	Open UI.mlx
	2	fill all user fields - assigned as controls:
                InitDate,EndDate 
       SourceFolder - Must be modified to the path of the project folder
       StocksCategory,InvestmentDuration
       ImportMat.Mine,ImportMat.Clean,ImportMat.Process - 
During first run must be unchecked, for later runs may be checked for quicker run by using saved .mat files
    AnalysisName


Easy Modifications:
	1	Modifiy stock groups @ ->functions/Mine/StocksBank
	2	Modify Plot Choice by tickboxes @ ->functions/Visualize/Plot Choice
Ready to Run.


Output:

	1	Updates the DB Folder with MAT files to be used for future quicker runs using the tick boxes.
	2	Updates the DB Folder with jpg files to save the results.

Example output is presnted in DB folder

Most informative histogram in my opinion is titled "Average Yearly Revenue Over The Chosen Time Period"

Most convient way of reviewing the results is by exporting the live Script to PDF,HTML, etc.

Other requirements:
slash "/" should be modified for windows
