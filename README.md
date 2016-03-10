# Csv2Excel
A java command line program that converts one or more csv files into an Excel spreadsheet with one tab per input file.

#Author
Jonathon Bowring

#Created Date
02/03/2016

# Usage 
Csv2Excel -t [xlsx|xls] -o [outfile] -d [delimiter] -e [input encoding] -i [infile1:infile2:infile3...]

# Example Usage (Pipe Delimited CSVs)
Csv2Excel -t xlsx -o myoutfile -d \\| -e UTF-8 -i mysheet1.txt:mysheet2.txt:mysheet3.txt

# Troubleshooting:
1) "Command not found.": If you are using a pipe delimiter it must be escaped with a slash. E.g. "-\|".<br />
2) "(No such file or directory)": Check you have the correct input/output file paths<br />
3) "Unable to access jarfile": Check you have the right path to the executable jar file and that it has the ".jar" extension. E.g. "/apps/MTD/infa_shared/RCN/scripts/Csv2Excel/Csv2Excel.jar".<br />
