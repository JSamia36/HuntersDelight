Modify these based on site-specific scenarios or dependent on what you need. There are many sources to find more, one of my favorites is https://taksec.github.io/google-dorks-bug-bounty/
I plan to clean this up further and seperate the dorks based on the results recieved from each. Please also note I did not come up with majority of these, these are just ones I have found other people sharing and often use.

# Google Dorks
``` 
site:example.com inurl:?id
site:example.com ext:php OR inurl:*.php? site:[domain].com
site:example.com ext:aspx
site:example.com inurl:”.php?cmd=”
site:example.com Index: Index of /wp-admin
site:example.com intext: “Index of /admin”
site:example.com filetype: log
site:example.com inurl:"loginsuccess" 
site:example.com password | secret | credentials | secret | SecretAccessKey | security_credentials -help
site:example.com -www -shop -share -ir -mfa -support
(site:example.com | site:example2.com) & ”choose file”
intext:register site:example.com
site:example.com inurl:.php?error
site:example.com inurl:error=error
site:example.comv inurl:cgi-bin
intitle:"index of /" "contact" site:example.com
site:example.com intext:"you don't have to use the web site, you can" -community -questions -forum -reddit -github -pdf -tutorials -support
site:example.comv inurl:index.cgi
inurl:*<*.example.com intext:"login" | intitle:"login" | inurl:"login" | intext:"username" | intitle:"username" | inurl:"username" | intext:"password" | intitle:"password" | inurl:"password"

```


