# Coding For Dummies

Reminder for noobs - like me


![Gopher](https://blog.golang.org/gopher/gopher.png)

## Git

- Delete a tag (local then remote)

```
git tag -d 1.0.0
git push origin :refs/tags/1.0.0
```

- Force reset to an old commit

```
git reset --hard dd61ab32^
git push master -f
```

## Unix

- List process (date sorting)

```
ps -ef --sort=start_time
```

- Massive delete (php process)

``` 
kill `ps -ef | grep php | awk '{print $2}'`
```
