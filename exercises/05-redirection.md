# Exercise 5: Redirection

## Goal
Learn how to save output into files.

## Tasks

1. Create a file called `output.txt` with the word "hello"
2. Append the word "world" to the same file
3. Display the contents of `output.txt`
4. Save all "ERROR" lines from `log.txt` into a file called `errors.txt`
5. Save all "INFO" lines into a file called `info.txt`

## Challenge

Create a file called `clean_errors.txt` that:
- contains only ERROR lines
- is sorted
- has no duplicates

## Hints

Use > to write output into a file.
Use >> to append to a file instead of replacing it.
Use cat filename to check the contents.
You can combine grep with > to save search results into a new file.