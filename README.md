# MemeTracker
## Version: 0.2.1

A programme to convert Copyfind outputs into a list of reprint matches for the creation of a list of memes; part of the [Scissors and Paste Project]( https://osf.io/nm2rq/)

### Input

The MemeTracker requires an input file in tab-separate value (.tsv) format. The file should have the data in the following columns, without a header.
+ Perfect_Match_Score
+ Left_Match_Score
+ Right_Match_Score
+ Target_Year
+ Target_Month	
+ Target_Day
+ Target_Title
+ Target_Identifier
+ Source_Year
+ Source _Month
+ Source _Day	
+ Source _Title 	
+ Source_ Identifier

Example inputs are available at [https://github.com/mhbeals/BL19thC_Reprints/tree/master/Formatted%20Matching%20Reports]( https://github.com/mhbeals/BL19thC_Reprints/tree/master/Formatted%20Matching%20Reports)

Example (catalogued) outputs are available at [https://github.com/mhbeals/BL19thC_Reprints/tree/master/Memes](https://github.com/mhbeals/BL19thC_Reprints/tree/master/Memes)

### Use

Run release candidate on Windows or open source in Visual Studio with an individual input

OR

Use script and batch file creator (python) to run a sequence of files
