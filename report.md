# DATA201 group project 

### by Cameron Pearce, Peter Nichols, Shaojie Li and Weidou Chen

The goal of this project was to create a datamodel that was accessable to people in New Zealand who are interested in looking at the underlying data
surrounding car accidents in New Zealand.

We decided to undertake this project as there is no single go to data source for the public to go to if they wish to research information about crashes in New Zealand 

# what data sources did we use and why did we choose these sources 

We looked at several data sources however quickly realised that there wasnt much to choose from, 
we eventually found a very large database that is also still currently being updated and contains current data, this was perfect for this project
as we want the data in the data model to be automated to the most recent data. On top of this the data was very raw and just a large culmination of data taken from Police in New Zealand.

One problem with the data set is that we couldnt find another dataset that was detailed enough to be able to merge them, this means that the data unfortunately only comes from one data source however this data source does contain data of over 800,000 crashes over the past 20 years. 


we got the raw data for the crashes in new zealand from
https://catalogue.data.govt.nz/dataset/crash-analysis-system-cas-data3/resource/0dfd1ddb-582a-4a21-9cab-298c0b592729


# what was our target 

Our target was people and data scientists who are interested in New Zealand crash data and our goal is to develop a data model that will help these people 

4) what difficulties have you overcome to wrangle the data into the target data model



# what techniques did we use? 

we wanted to use techniques to wrangle the data such that would if there was a change in the column names or variable names or addition of new ones it would not break the program that gathers the data, one way of doing this is through the use of regex's, which we used to match key words to variables, for example the use of regex's to sort the data by region, we can search for multiple words in the column (canterbury, christchurch and chch) to esure that if there is a change in variable name that it will still be sorted correctly

![image](https://user-images.githubusercontent.com/97574130/197939530-208d1aa1-ed84-43a2-9e78-22cf8d55be28.png)


6) what you managed to achieve and what you failed to do 
