#COVID19-KeyCon-Viewer

COVID19 Keyword Convergence Viewer: 

JSON to TXT Converter and Multiple Keyword Search for COVID-19 Data Set (CORD-19)

This Powershell script provides a workflow for accessing and searching the full-text of COVID-19 research articles available here: https://pages.semanticscholar.org/coronavirus-research.

Once the data set is downloaded, expand zipped folders. Research article files will be in JSON format. Copy JSON files into a folder on your desktop named "Covid19_Keyword_Search," and then run this Powershell script. 
NOTE: New to Powershell or on a government computer? Run this script in Powershell by copying/pasting the text into Powershell, selecting all text, and then clicking "run selection."

Script allows multiple key term search of all JSON files (up to 10 terms). Exports results as follows: 1) CSV list showing file name and lines of text containing individual search terms, and 2) a single, merged text file of all articles where all search terms converge (i.e. hits contain ALL search terms). This is an important search functionality to have with this textual data because researchers need to see cause and effect relationships and document other complicated relationships that cannot be determined through more basic search. 

NOTE: The data set currently contains about 30k JSON objects. Running a search for a frequently appearing term will take a while.

Apologies to Powershell PROs who will see the clunkiness of some of my scripting, but it works to get the job done! I wrote this to give better access to a wider audience of researchers who don't know what to do with JSON objects and whose insights into this data could help us solve the current COVID-19 crisis or prevent future ones.
