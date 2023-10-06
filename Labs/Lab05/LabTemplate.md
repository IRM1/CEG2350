## Lab 05

- Name:
- Email

## namechange Usage Guide

Examples of script usage and output. This should be enough info that  
you can hand this and the script to someone not in this course and they  
would be able to understand what your script does and how to use it.

Use good markdown so that this documentation is pretty and clean on GitHub.

ANSWER
# namechange script guide


`If you want to change a part of your file name for e.g from file.tmt to file.txt you can use this file`

# syntax to use this script

`./namechange -f "here put the text you want to change" -r "what you want it to replaced with" "file name you want to change"`


# examples of input

`./namechange -f ".tmt" -r ".txt" "file.tmt"`

# output will be

`Rename "file.tmt" to "file.txt"

# input

`./namechange -h`

# output

`Usage: ./namechange -f pattern_to_find -r replacement string_to_modify
 -f Specify a pattern to find in the filename
 -r Specify what to replace the found pattern with in the filename
 -h Display this help message and exit`

# input
`./namechange -x`

# output

`Invalid option: -x
Usage: ./namechange -f pattern_to_find -r replacement string_to_modify
 -f Specify a pattern to find in the filename
 -r Specify what to replace the found pattern with in the filename
 -h Display this help message and exit`

# input

`./namechange -f ".tmt" -r ".txt"

# output

`User must provide a valid filename
Usage: ./namechange -f pattern_to_find -r replacement string_to_modify
 -f Specify a pattern to find in the filename
 -r Specify what to replace the found pattern with in the filename
 -h Display this help message and exit`
