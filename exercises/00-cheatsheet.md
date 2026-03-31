# Linux Cheat Sheet

## Navigation
pwd        # show current directory
ls         # list files
cd folder  # go into folder
cd ..      # go back

## Files
cat file.txt     # show file contents
head -n 3 file   # first 3 lines
tail -n 2 file   # last 2 lines

## Creating
mkdir test       # create folder
touch file.txt   # create file

## Searching
grep "word" file.txt
grep -c "word" file.txt

## Pipes
|                # pass output to next command

## Redirection
>  overwrite file
>> append to file