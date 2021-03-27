# Python-homework
from pathlib import Path
import csv
line_num = 0

with open('PyBank.csv')as csvfile:
    csvreader = csv.reader(csvfile, delimiter=',')
    header = next(csvreader)
    line_num += 1

    print(f"{header} <---- PyBank Analysis Report")  
    for row in csvreader:
        date = row [0]
        profitandlosses = (row[1])
        print (date)
        print (profitandlosses)

total_profitandlosses = 0
average_profitandlosses = 0
maximum_profitandlosses= 0
miminum_profitandlosses= 0
count_profitandlosses = 0

for profitandlosses in profitandlosses:
    
        total_profitandlosses += profitandlosses
        count_profitandlosse += 1

if miminum_profitandlosses == 0:
        miminum_profitandlosses = profitandlosses
elif maximum_profitandlossessalary >maximum_profitandlosses:
        maximum_profitandlosses = profitandlosses
elif salary < miminum_profitandlosses:
        miminum_profitandlosses = profitandlosses
    
count_profitandlosse+= date
totalprofitandlosses = date

average_profitandlosses  = round(total_profitandlosses / count_profitandlosse , 2)
