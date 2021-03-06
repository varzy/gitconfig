# .gitconfig

My own ".gitconfig" file.

```
[user]
  name =
  email =

[alias]
# basic
  i = init
  ib = init --bare
  a = add
  aa = add .
  c = commit
  cm = commit -m
  cl = clone
  cll = clone --depth 1
  sts = status
  st = stash
  stp = stash pop
  re = remote
  rb = rebase
  # sm = submodule

# push
  ps = push
  pso = push origin
  psom = push origin master
  psot = push origin --tags
  psou = push origin -u

# pull
  pl = pull
  plr = pull --rebase
  plo = pull origin
  plom = pull origin master

# fetch
  fe = fetch
  feo = fetch origin

# branch
  b = branch
  bd = branch -d
  bD = branch -D

# tag
  t = tag
  td = tag -d

# merge
  mg = merge
  mgn = merge --no-ff

# checkout
  co = checkout
  cob = checkout -b
  coo = checkout --orphan

# reset
  rs = reset --hard
  rsl = reset --hard HEAD^

# log
  lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
  rlg = reflog

[http "https://github.com"]
  proxy = socks5://127.0.0.1:1080

[https "https://github.com"]
  proxy = socks5://127.0.0.1:1080

# encoding
[core]
  quotepath = false

[gui]
  encoding = utf-8

[i18n "commit"]
  encoding = utf-8

[i18n]
  logoutputencoding = utf-8
```
