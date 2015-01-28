# HIST3907
## M02E04 Notes
## January 27, 2015
-----
Exercise Directions: [https://github.com/hist3907b-winter2015/module2-findingdata/blob/master/m2-exercises.md](https://github.com/hist3907b-winter2015/module2-findingdata/blob/master/m2-exercises.md)

Working with [https://ianmilli.files.wordpress.com/2015/01/downloading-sources2.pdf](https://ianmilli.files.wordpress.com/2015/01/downloading-sources2.pdf)

I have decided to restrict the size of the ItemList.txt to only 10 items to reduce processing time.
Can replicate process easily if more records are required later in the exercise.
Files stored locally at C:\Users\Patrick Kelley\Documents\HIST3907B\Module02\Exercise04.

Using Search-M02E04-v04.csv to create ItemList.txt
Version 3 contains over 8k records and would break my computer...

Initial attempt to Save As... from CSV in excel failed.  Saving the ItemList.txt by copying data from Excel and pasting it directly into Notepad did the trick.

Use this command:
wget -r -H -nc -np -nH --cut-dirs=2 -A .txt -e robots=off -l1 -i ./itemlist.txt -B 'http://archive.org/download/'

Output stored locally at C:\Users\Patrick Kelley\Documents\HIST3907B\Module02\Exercise04\Output

Success!
Saving the ItemList.txt by copying data from Excel and pasting it directly into Notepad did the trick.

Copying items to Repo and syncing with Github.





