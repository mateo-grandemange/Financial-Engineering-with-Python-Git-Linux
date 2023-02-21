# TD3/9: Work with text manipulation tools in
Linux
Exercise 1: Grep and awk on tabular data
1. Display the list of files and folders at the root using ls -l
2. In a pipeline (using |), append a grep instruction to only display informations of bin
3. Append an awk instruction to only display the size of bin
4. Now rather extract the month, day and year of creation of the folder bin
5. Now rearrange the instruction to get the following output format : 2020-
Oct-26 (from original data : Oct 26 2020)
Exercise 2: Grep with Regex, and sed on unstructured
data
1. Run the following command :
curl https ://en.wikipedia.org/wiki/List_of_cyberattacks > cyberattacks.txt
2. Use grep to extract all the lines that contain the keyword "meta"