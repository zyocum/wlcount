#`wlcount`
Count frequency of word lengths in text files.

This script splits all words in a file based on whitespace and counts how many
words of each character length are present.  The script reports the counts in
a tabular format with the first column being a character length and the second
column being the number of words in the file that are that length in characters:

    ==> filename <==
    Length	Count
    N	M

Where filename is the name of the file, N is a character length, and 
M is the number of words that are N characters in length.

You can use `wlcount` by passing it paths to text files:

    usage: ./wlcount file [file ...]

For example, `wlcount` can be run on itself, since it is a Python script:

    ./wlcount wlcount
    ==> wlcount <==
    Length	Count
    1	10
    2	28
    3	27
    4	19
    5	18
    6	21
    7	14
    8	6
    9	6
    10	5
    11	6
    12	2
    13	2
    14	1
    16	1
    17	3
    20	1
    21	1
    23	2
    24	1
    38	1
