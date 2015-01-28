# M02E04
## wget flag notes
## January 28, 2015
-----
See [http://www.gnu.org/software/wget/manual/wget.html](http://www.gnu.org/software/wget/manual/wget.html)
-----
recall syntax used in executing wget portion of exercise:
wget -r -H -nc -np -nH --cut-dirs=2 -A .txt -e robots=off -l1 -i ./itemlist.txt -B 'http://archive.org/download/'

What does this mean in layman's terms?
-----
'-' is a flag
'-' is followed by an operator, e.g. '-i'
Further operators can follow the initial one. e.g. '-crc URL'
'--' terminates preceding operator and moves on to the next?  (Is this correct?)

So let's rewrite the above command and separate each operator out into a line by line format so that we can understand it better.

*wget
 *'-r  Recursive.
 *'-H  Enable spanning across hosts when doing recursive retrieving (?)
 *'-nc  no-clobber.  Prevents multiple versions from being downloaded and written.
 *'-np  Do not ever ascend to the parent directory when retrieving recursively.
 *'-nH  Disable generation of host-prefixed directories.  (So not creating dirs on the harddrive?)
 *'--  (Does this terminate the nh flag?  Or inidcate that 'cut-dirs' is a sub-flag to nH?)
 *'cut-dirs=2  Ignore number directory componenets.
 *'-A .txt  Accept acclist.  (?) (Some options indicate regex in the guide.  Given that this is a chapter in Prof Graham's online book, is this relevant?)
 *'-e robots=off (?)
 *'-l1 Level depth for recursive download.  (?)
 *'-i ./itemlist.txt  Identifies input file name.  './' indicating that it is in the same folder as the script.
 *'-B 'http://archive.org/download/'
