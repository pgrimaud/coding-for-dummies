# Coding For Dummies

Reminder for noobs - like me


![Gopher](https://blog.golang.org/gopher/gopher.png)


## Appengine

- Download a project

```
appcfg.py download_app -A MyAppName PathFolder
```

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

- Edit a user crontab

```
crontab -u www-data -e
```
- Massive delete (php process)

``` 
kill `ps -ef | grep php | awk '{print $2}'`
```
- Install & use mtr

```
brew install mtr
/usr/local/sbin/mtr 8.8.8.8
```

- Copy local key to server

```
ssh-copy-id -i ~/.ssh/id_dsa.pub user@server
```
