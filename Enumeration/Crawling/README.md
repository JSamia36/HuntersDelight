I decided to seperate this from Path-Discovery for the potential to include more down the road as well as my own personal convience 
# Single URL
```
$ katana -u example.com -jc -o params.txt
$ ffuf -u example.com/FUZZ -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt >> paths.txt
$ paramspider -d example.com
$ echo 'example.com' | waybackurls >> params.txt
```
# Multiple URLs
```
$ cat domains.txt | katana -jc >> params.txt
$ cat domains.txt | waybackurls >> params.txt
$ cat domains.txt | gau >> params.txt
$ paramspider -l domains.txt 
```
