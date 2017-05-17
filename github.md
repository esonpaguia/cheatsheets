# Github cheatsheet

## Links
- [How do I link my domain to GitHub Pages](https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages)

## Create a CNAME file
- The file must be located in the root directory of your username.github.io repository.
- The file must only contain your bare domain name. Eg. esonpaguia.com

## Advanced DNS settings
- A record for @ pointing to 192.30.252.153
- A record for @ pointing to 192.30.252.154
- CNAME record for www pointing to your username.github.io

## Verify
- Verify A record
```
dig esonpaguia.com +nostats +nocomments +nocmd
```

- Verify CNAME record
```
dig www.esonpaguia.com +nostats +nocomments +nocmd
```
