# Test `git-crypt`

Get from : https://github.com/AGWA/git-crypt

```
$ git-crypt init
```

```
$ cat .gitattributes 
* filter=git-crypt diff=git-crypt
.gitattributes !filter !diff
README.md !filter !diff
```

```
$ git-crypt add-gpg-user 6A886CD6
```



