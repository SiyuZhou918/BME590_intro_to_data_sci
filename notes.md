# intro to data science:

## Lec2_Sep4
power calculation: find numbers of sample we need

tips:
1. print("value 1 = {0}   and    value 2 = {1}".format(v1, v2))

print("value 1 = {1:7.2f}   and    value 2 = {0}".format(5.33, 1.30))
value 1 =    1.30   and    value 2 = 5.33


## Lec2_Sep6
assignment requirement: test if your work is handy in AI tool

conda -n 
conda install numpy
curl
mv

./ current folder
../ parent folder


delete folder:
rmdir bme590
rm -r bme590

head, tail: take the first(last) few lines of file
 head/tail -20 filename 
sort: sort a file on any field
shuf: shuffle lines of a file
grep: select for (or against) lines that match a pattern
sed: apply a search/replace pattern to each line
awk: command line scripting language

grep -v "^#" filename | head -5
sort -k3 -n <filename>
filename | sort | head 
filename | sort | head | sort
grep -v "^#" filename | awk '{print $1}' | sort > foo

comm help
grep -v "^#" filename | sort -n -r -k2 | head -5
grep -v "^#" filename | sort -nr -k2 | head -5

# deep learning
3d color image
4d color image video
5