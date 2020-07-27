# Movies-ETL
## Assumptions made during the process
1. This piece of code only works for the same/similar data set that was worked on earlier. That is, it works on one json file and two csv files that are specifically have a movie database. 
2. More specifically we assume that the data is the same too and not that different form the files we worked on for the module. To have a more generalized etl process that is both automated and does the extraction, transformation and loading we would have to relax the specification that are considered.
3. The parsing process is done based on what the data types of certain columns should be. The other columns were not changed since we did not see them as incorrect but this could of course be wrong and there could be errors in the columns that we did not investigate too. 
4. Overall this process is done based on the data we need since it would be a time consuming task to look at all the data and to try and sort everything out. 
5. The try-except method takes care of the unforseen errors that we may not see during the initial investigating process.
6. This method is after all based on the individual as each person may look at data differently. While some may think that they could fix the data others may think that the data just needs to be dropped. 
7. There were some processes that had to be removed since the whole thing was automated so we are assuming that the dataset does not have too many irregularities. These processes including looking at the datastructure and identifying what must be done to the data. We just mostly assumed that the wikipedia data had columns that needed to be dropped and had to be cleaned and the csv files were fairly clean. 
