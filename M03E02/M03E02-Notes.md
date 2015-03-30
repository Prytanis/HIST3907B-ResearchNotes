# Module 03 Exercise 02
## Notes

### A gentle introduction to Regular Expressions

Everything seems pretty self explanatory.  . instead of *, though.  Why?  Whatever.  Doesn't matter.

###  Don't Mess with Texas: Get the Data

http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt

Used view source.
Copy - pasted relevant text into notepade document.
Path: C:\Users\Patrick Kelley\Documents\HIST3907B\Module03\Exercise02
File: DigitizedText01.txt
Renamed: texan-correspondence-v01.txt

Deleted non-table of contents stuff...
texan-correspondence-02.txt

### Step One

Replace with an tilde prefix complete.
File: texan-correspondence-03.txt

### Step Two
Removed unflagged lines easily.  Could not have figured out the Regex expression on my own.
File: texan-correspondence-04.txt
I thought: "But it left blank line?!"  and then I saw the notes for step three...

### Step Three
Executed as described.  Still many blank lines remaining.  Checked blank lines for spaces, for example, nothing there.  Can't explain.
Resolving with export into csv and export to .txt.
File: texan-correspondence-07.txt
By product is that list has been sorted alphabetically.  Hopefully won't effect future steps.

### Step Four
So, why is it that this exercise requires us to use '$' when this has not been previously discussed?  What a waste of time.
File: texan-correspondence-08.txt

### Step Five
Tildes gone.
File: texan-correspondence-09.txt

### Step Six
RegExr not very helpful on this step for some reason.  Handled with ".\<to\>"
File: texan-correspondence-10.txt

### Step Seven
Manual deletion of commas and one line item complete.
File: texan-correspondence-11.txt


