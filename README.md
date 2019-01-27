# 0xff-repo


- **maintaining the repo:**

 build/rebuild:

``` 
$ cd /path/to/repo
$ repose 0xff-repo --files --root=x86_64/ --rebuild
```


 list packages:

```
$ cd /path/to/repo
$ repose 0xff-repo --list --root=x86_64/
```


 check and update packages:
```
$ aursync --repo  0xff-repo --root --root=x86_64 -u
```
