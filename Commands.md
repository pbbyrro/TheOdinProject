1. **cd**: change directory
<br>cd without an argument will return you to your home directory
2. **cd -**: the previous directory I was in
3. **ls**: lists the content of the current directory in alphabetical order by name
4. **ls -t**: lists the content of the current directory by time of last change
5. **ls -r**: lists the content of the current directory in reverse order
6. **ls -rt**: most recently changed file is listed last
7. **ls -s**: displays the size of files and directories alongside the names
8. **ls -S**: sorts the files and directories by size
9. **pwd**: print working directory - shows you where you are
10. **-F**: adds a marker to file and directory names to indicate what they are
<br>/ indicates its a directory; @ indicates a link; * indicates an executable
9. **. .**: the parent of the current directory (the directory containing this one)
10. **-a**: show all (including hidden files)
11. **mkdir [path]**: creates new directory
12. **mkdir -p**: creates directory with nested subdirectories in a single operation
13. **touch**: generates a new file in your current directory
14. **mv**: move (overwrites existing files with the same name)
15. **mv -i**: requests for confirmation before overwriting files
16. **cp [old] [new]**: copies a file
17. **cp -r**: copies a directory and all its contents
18. **rm [path]**: remove (only works on files)
19. **rm -r**: removes a directory and all its contents
20. **"*"** (without "): wildcard that represents zero or more characters in a file name
21. **?**: wildcard that represents exactly one character in a file name
22. **wc**: counts the number of lines, words and characters in files
23. **wc -l**: counts the number of lines per file
24. **wc -m**: counts the number of characters per file
25. **wc -w**: counts the number of words per file
26. **sort**: sorts the contents of files in alphabetical order
27. **sort -n**: sorts the contents of files in numerical order
28. **command > [file]**: tells the shell to redirect the command's output to a file
29. **command >> [file]**: tells the shell to append a command's output to a file
30. **cat**: concatenate; prints the contents of files one after another
31. **head**: get the first 10 lines
<br>head -n 1: only shows the first line of the file
<br>head -n 20: shows the first 20 lines of the file
31. **tail**: gets the last 10 lines of the file
32. **echo**: print strings
33. **[first] | [last]**: use the output of the command on the left as the input to the command on the right
34. **cut**: removes certain sections of each line in the file
35. **cut -d**: delimiter character
36. **uniq**: filters out adjacent matching lines in a file
37. **uniq -c**: counts the number of times a line occurs in its input
