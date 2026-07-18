Day 3 - reading files and pipes
cat=dump, head=first lines, tail=last lines, tail -f=follow live, less=scroll (q to quit)
grep PATTERN file=filter lines
| pipes left output into right input
wc -l counts lines
pipe is essential when left side is not a file: ls -l | grep .txt
