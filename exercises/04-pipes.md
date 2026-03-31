# Exercise 4: Pipes

## Goal
Learn how to combine commands using pipes.

## Tasks

1. Sort the contents of `fruits.txt`
2. Remove duplicate lines from `fruits.txt`
3. Combine sort and unique together
4. Count how many times "banana" appears using pipes

## Bonus
Try chaining 3 commands together

## Hints
Use grep "word" file | wc -l to count matching lines with a pipe.
Use sort filename to sort lines alphabetically.
Use uniq to remove repeated adjacent lines.
If duplicates are not next to each other, use sort before uniq.
