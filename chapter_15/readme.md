|Question | Answer |
|---------|-----------
|Can you put "This class is fun" into bar.txt?|$echo 'This class is fun' > bar.txt|
|Can you put "Oh so much fun" into foo.txt?|$echo 'Oh so much fun' >foo.txt|
|Explain in own words what the following do:||
|'\|'|  This redirects output from one command to another.  I could use this to pipe output from ls or find to pbcopy to copy output to clipboard|
| > | Redirects output to a file.  I could echo text to a file i.e. echo 'Howdy' > howdy.txt or output ls to file $ls > dir_output.txt |
| < | Pulls input from a source to your command.  Like, $cat < howdy.txt
| >> | Appends output to a file $echo 'Howdy howdy howdy' howdy.txt would add the line to the bottom of howdy.txt |
