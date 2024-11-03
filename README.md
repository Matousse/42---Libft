# Project Libft

# Goal of the project
libft is a C library created for the 42 curriculum. It includes utility functions for string manipulation, memory management, and basic data structures.

# Contents
String manipulation functions (e.g., ft_strlen, ft_strcpy)
Memory management functions (e.g., ft_malloc, ft_free)
Conversion and formatting functions (e.g., ft_atoi, ft_itoa)
Basic data structures (e.g., linked lists)




./pipex infile "cat" "wc -l" outfile
./pipex infile "grep '42'" "wc -w" outfile
./pipex infile "ls -l" "sort -r" outfile
./pipex infile "awk '{print $1, $3}'" "sort" outfile
./pipex infile "awk '{if (\$2 > 10) print}'" "grep 'somepattern'" outfile
./pipex infile "tr 'a-z' 'A-Z'" "wc -c" outfile
./pipex infile "cut -d ' ' -f 1" "uniq" outfile
./pipex infile "sed 's/42/1337/g'" "wc -l" outfile
./pipex infile "head -n 10" "tail -n 5" outfile
./pipex infile "/bin/nonexistentcommand" "wc -l" outfile
