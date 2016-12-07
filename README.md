# .gitconfig

自用的 .gitconfig 文件配置。

```
[user]
  name = 
  email = 

[alias]
# basic
  i = init
  a = add
  c = commit
  cl = clone
  st = status

# push
  p = push
  po = push origin	
  pom = push origin master

# branch
  b = branch
  bd  = branch -d
  bD  = branch -D

# checkout
  co = checkout
  cob = checkout -b

# merge
  mg = merge

# reset
  rs = reset --hard
  rslast = reset --hard HEAD^

# tag
  t = tag
  td = tag -d

# remote
  re = remote

# log
  lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit

[http]
  proxy = socks5://127.0.0.1:1080
[https]
  proxy = socks5://127.0.0.1:1080
```
