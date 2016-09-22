# Scripts

My scripts for work.

## Install

```
$ git clone https://github.com/liubin/scripts ~/scripts
$ export PATH=~/scripts:$PATH
$ chmod +x ~/script/*
```

## Command list


### dke

Docker kill Exited container:

```
$ dke
Removing 630f17f03600
630f17f03600

Removing 699872b3712c
699872b3712c
```

### dip

Show Docker container IP:

```
$ dip post
IP for conatiner /peaceful_curran (bb8a0fc140ef) is 172.17.0.3
IP for conatiner /postgres (5073328a4fb2) is 172.17.0.2
```

### gc

If you frequently switch with two branches, you may be like a command as `cd -` to return the previous directory. `gc` will do the same.

[gc(git checkout) doc](docs/gc.md)

[![asciicast](https://asciinema.org/a/drprjbjaz46py8db8brea1muu.png)](https://asciinema.org/a/drprjbjaz46py8db8brea1muu)

### dexec

Simply warpper to help you exec commands in containers easy.

[dexec(docker exec) doc](docs/dexec.md)

[![asciicast](https://asciinema.org/a/b9bxcyf4iamfnoc8wzu3udm3i.png)](https://asciinema.org/a/b9bxcyf4iamfnoc8wzu3udm3i)