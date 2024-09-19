Please note I am putthing the same wordlist for the different tools right now, please switch the wordlist to your preferred. I plan to update this at a later time once the rest of this project is sculpted a bit more.

# Single URL
```
$ gobuster dir -u example.com -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt >> paths.txt
$ ffuf -u example.com/FUZZ -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt >> paths.txt
$ paramspider -l example.com >> paths.txt
