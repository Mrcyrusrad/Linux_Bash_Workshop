# Exercise 4: Pipes

## Goal
Learn how to combine commands using pipes.

## Tasks

1. Count how many times "ERROR" appears using a pipe
2. Sort the contents of `fruits.txt`
3. Remove duplicate lines from `fruits.txt`
4. Combine sort and uniq together
5. Count how many times "banana" appears using pipes

## Bonus
Try chaining 3 commands together

## Hints
Use grep "word" file | wc -l to count matching lines with a pipe.
Use sort filename to sort lines alphabetically.
Use uniq to remove repeated adjacent lines.
If duplicates are not next to each other, use sort before uniq.