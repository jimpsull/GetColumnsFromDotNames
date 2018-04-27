# GetColumnsFromDotNames
Semi-automatic process to get column headers from .names file without having to type them.

The purpose of this file is to reduce the need to manually type column names for the archive.ics.uci.edu/ml/.. datasets.  It is semi-automatic in that it does some of the heavylifting but you'll still need to review its conclusions and likely make tweaks.To use the file paste the text from the .names file into the Names Template worksheet cell A4.Then copy and paste cells G1:G2 to H1:H2 as values.  G2 will be text you can use to set yourdataFrame's column names.  H2 can be used for column headers (text --> columns , delimited)if you wish to review the data in Excel.

I have run this tool twice on example data:

https://archive.ics.uci.edu/ml/machine-learning-databases/horse-colic/horse-colic.namesfor this file it treats columns 25, 26, 27 as one column.  You'll need to modify to match the data

https://archive.ics.uci.edu/ml/machine-learning-databases/dermatology/dermatology.namesfor this file it presents the attributes out of sequence (11, 34, 12)for this file it presents 34 attributes when the dataset contains 35
