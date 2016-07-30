# Test `git-crypt`

Get from : https://github.com/AGWA/git-crypt

Get from brew:
```
$ brew install git-crypt
```


Init repo:
```
$ git-crypt init
```

Edit `.gitattributes` file:
```
$ cat .gitattributes 
* filter=git-crypt diff=git-crypt
.gitattributes !filter !diff
README.md !filter !diff
```

Add GPG user:
```
$ git-crypt add-gpg-user 6A886CD6
```

Unlock after clone:
```
$ git-crypt unlock
```



