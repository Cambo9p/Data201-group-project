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

another problem was the sheer size of the raw data, taking several minutes to download and over 800,000 columns, to make the dataset easier to work with we decided to filter the columns so that the data is onlly for the crashes in the canterbury region.


we got the raw data for the crashes in new zealand from
https://catalogue.data.govt.nz/dataset/crash-analysis-system-cas-data3/resource/0dfd1ddb-582a-4a21-9cab-298c0b592729


# what was our target 

Our target was people and data scientists who are interested in New Zealand crash data and our goal is to develop a data model that will help these people.

My hope was to create a package that the user can download and run one file and all the data off the internet is compiled and filtered nicely for them to use. 

# what difficulties have you overcome to wrangle the data into the target data model

We found significant difficulty in finding a way to automate the columns in a way where all the csv files were correctly populated. 
Eventually we ran out of time and only managed to automate the speed columns as this was fairly trivial, and the regions to slim the dataset down to the canterbury region.



# what techniques did we use? 

we wanted to use techniques to wrangle the data such that would if there was a change in the column names or variable names or addition of new ones it would not break the program that gathers the data, one way of doing this is through the use of regex's, which we used to match key words to variables, for example the use of regex's to sort the data by region, we can search for multiple words in the column (canterbury, christchurch and chch) to esure that if there is a change in variable name that it will still be sorted correctly

![image](https://user-images.githubusercontent.com/97574130/197939530-208d1aa1-ed84-43a2-9e78-22cf8d55be28.png)


# what you managed to achieve and what you failed to do 

We managed to create and compile a data model from the internet, this is in a relatively easy to access package with just a few steps to download and create the data, with the user only having to run 2 files to reproduce the data, this was made possible through the use of notebook merging.

however it has many flaws. first off a lot of the table columns are hard coded choices, I simply didnt have enough time to even think about how I was going to achieve this goal.

# What we failed to do

The project is not close to finished, if I had more time here is a short list of the things I would do

1 ) fix the merge files 

it was not clear at the start how we would get everything into one file and make it easy to run all the code, unfortunately due to this I created a lot of seperate files to work with different csv files for ease of debugging and making it easy to read, unfortunately this means that when it comes to merging the files sequentially, the library tidyverse is imported several times as it is as the top of many files, aswell as importing the same files multiple times, this is obv extremely bad practice however i do not have the time to fix it as this ended up being a one person project.

2) automate the data better

My goal for this project was for the data model produced to be robust and be able to change what columns ended up in what tables by itself, meaning that the use of this project would be self sustaining, unfortunately this is vastly unfinished, as the only operations that wont be affected by the changing of the raw data would be the speed file and the sorting of the data into the canterbury region. 





