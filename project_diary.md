# project diary for Data201 

further information about who made what commits can be found at the github page 
https://github.com/Cambo9p/Data201-group-project


## 3/08/22 - cpe79 
	reached out to group members about project - created discord group chat for the members to talk about project


## 10/08/22 - cpe79 
	sent follow up message asking what ideas for the project the other members had


## 12/08/22 - cpe79 
	organised to meet members on firday at 2pm 


## 13/08/22 - cpe79 

    created git page along with readme, project diary and added in the information we have about the project into the repo 


## 14/08/22 - cpe79 

    met with Shaojie and Weidou and we decided on a project and a data source 
    we decided that we would investigate crashes in chch 
    meeting lasted about an hour


## 15/08/22 - cpe79

    worked at home - imported csv file into R and filtered by crashes in chch
    also fixed github things such as documentation, 
    emailed thomas asking for an extension,
    

## 16/08/22 - pni31 
    
    searched for additional data sources to use


## 16/08/22 - cpe79 

    refactored bar graph from crash page 
    looking into other datasets to get information from 
    created and started on report 
    created and completed .ipynb files to create the tables for the date model 


## 17/08/22 - cpe79 

    created relationship diagram and edited code to add fields to the csv files 
    

## 18/08/22 - pni31 

    data model now creates RDS file 
    created graphs from different files to represent data in visual form


## 18/08/22 - cpe79 
	started and finished presentation for the data we have collected
	looked into automating the datamodel to update with the newest information 


## 20/08/22 - cpe79 
	played around with different packages to find a way to automatically download the csv file 
	from the internet 
	began reorganising code as theres too many files that are useless
	automated downloaing of the datamodel
	automated column filtering using regexs to account for a sudden change in variable name for region


## 21/08/22 - cpe79
	worked on automating the creation of the data model 
	-- looked into having one script that runs all of the necessary files to 
	produce the data 


## 23/08/22 - cpe79 
	looked into 'merging the jupyter notebooks rather than running them all at once 
	as im not sure running them all at once will work since there are notebooks using different kernels 
	- seems to work only when using ipython kernel 

	added content to the project report


## 26/08/22 - cpe79 
	still trying to find a way to combine the notebooks, i have a way to merge python files but not r files

	finally finished working on the merging of the files 

	added to project report 
	kept working on better ways to automate the data model (regex's to determine what columns are in 
	what files ect) 


## 28/08/22 - cpe79 

	changed readme to display the new way of producing the datamodel 
	worked on create_speed file to automate what columns go into the speed.csv file,
	this means that any changes in variable names or additions of new names to the main file 
	shouldnt break the data model 


## 29/08/22 - cpe79
	finished code for speed.csv where it automatically chooses the columns based off of the 
	name using regexs


## 30/08/22 - cpe79
	worked on project diary and made sure the project was functioning 
	re-ran all cells 
	refactored project diary to make it readable 
	
	

