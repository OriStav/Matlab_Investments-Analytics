Stocks Analysis
==============

***Summary:*** 
>Plots comparative histograms and graphs which describe thestocks performance over history, and the revenues for the chosen time parameters.

***Description:***
>>Steps:  
		1.	Open UI.mlx.   
		2.	fill all user fields - assigned as controls:    
			InitDate,EndDate  
	       SourceFolder - Must be modified to the path of the project folder  
	       StocksCategory,InvestmentDuration  
	       ImportMat.Mine,ImportMat.Clean,ImportMat.Process -   
			During first run must be unchecked, for later runs may be checked for quicker run by using saved .mat files  
	    3.AnalysisName  


>>Easy Modifications:  
	1.	Modifiy stock groups @ ->functions/Mine/StocksBank  
	2.	Modify Plot Choice by tickboxes @ ->functions/Visualize/Plot Choice  
Ready to Run.  


>>Output:  
	1.	Updates the DB Folder with MAT files to be used for future quicker runs using the tick boxes.  
	2.	Updates the DB Folder with jpg files to save the results.  

>Example output - 3 year investment analysis:
more graphs are presented in DB folder  
![NewHistComp](https://user-images.githubusercontent.com/111699131/219856905-7ab9fb2f-cab5-4a3e-8cf6-eecd74a2b13d.png)
![RevTimeComp](https://user-images.githubusercontent.com/111699131/219856920-07148098-5c70-48dd-b8fa-b28de40a6452.png)

Most informative histogram in my opinion is titled "Average Yearly Revenue Over The Chosen Time Period"  
Most convient way of reviewing the results is by exporting the live Script to PDF,HTML, etc.

***Other requirements:***
>slash "/" should be modified for windows

[![View Investments-Analytics on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/124920-investments-analytics)
