Please note you need the programs installed in order for the commands to work. Please visit the pages github to see the installation guide as it is not included here. 

# Single URL
``` 
$ subfinder -d example.com -o subs.txt
$ assetfinder -subs-only example.com >> subs.txt
$ python3 crtsh.py -d example.txt >> subs.txt
$ aquatone-discover --domain example.com >> subs.txt
$ ffuf -w /subdomain_megalist.txt -u 'https://FUZZ.example.com' -c -t 350 -mc all -fs 0 >> subs.txt
$ dnsx -d example.com -w /usr/share/seclists/discovery/Discovery/DNS/subdomains-top1million-2000.txt >> subs.txt
$ asnmap -d example.com >> subs.txt
$ echo example.com | alterx -enrich

```

# URL list
```
$ subfinder -dL example.txt -o subs.txt
