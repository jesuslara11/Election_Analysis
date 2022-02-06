# Election_Analysis
                        1) Overview of Election Audit
   The Purpose of this Analysis is to create an automated process to see the voter tunrout in each of the counties, which county had the highest voter turnout, and to create a breakdown of the percentage of votes between the counties.
   
                        2) Election Audit Results
    1)count the total votes: 369,711
    2)Votes by County : denver(306,055),Jefferson(38,8855), Arapahoe(24,801)
    3)largest county turnout: Denver 
    4)votes for each candidate with a percentage: stockham 23%, DeGette 73.8%,
    Doane 3.1%
    5)who was the winner, winners vote count and winner percentage of the votes: Diana Degette 

                        3) Election Audit Summary
   This script can be used to automate the process of counting votes and determine the winner of the election. However, there will have to be a couple modifications made to make it work. Frist you will have to change the data source of the script. You will change it to correct spreadsheet of results, both the path of the file and the name of it (code below listed as "A". Second you will want to change the name to the txt file created. As you will want to name it election results (State name), as it will create an easier way to find the results (Code below listed B). The script on its own will add the new candidates, results, and winner on its own, once the data source is updated.
    
    Line of code referenced in question 3.
     A) "file_to_load = os.path.join("/Users/jesuslara/Desktop/Election_Analysis/Resources","election_results.csv")
     B) file_to_save = os.path.join("analysis", "election_analysis.txt")
     

