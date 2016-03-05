# Csv2Excel
A java command line program that converts one or more csv files into an Excel spreadsheet with one tab per input file.

# Details
Author: Jonathon Bowring
Created Date: 02/03/2016

# Usage
Usage: Csv2Excel -t [xlsx|xls] -o [outfile] -d [delimiter] -i [infile1:infile2:infile3...]

# Example Usage (Pipe Delimited CSVs)
Csv2Excel -d \| -t xlsx -o /home/foo/Documents/myoutfile -i /home/foo/Documents/mysheet1.txt:/home/foo/Documents/mysheet2.txt:/home/foo/Documents/mysheet3.txt
