# Bash Tools for TYPO3

## Install: 
```
git clone git@github.com:Startpiloten/bin_t3.git ~/bin_t3
```

### If you use .profile 
```
(echo 'export PATH=$PATH":$HOME/bin_t3"') >> ~/.profile
```

### If you use .bash_profile 
```
(echo 'export PATH=$PATH":$HOME/bin_t3"') >> ~/.bash_profile
```

## Update 
```
(cd ~/bin_t3 && git fetch --all && git reset --hard origin/master)
```

## Available Commands

### t3-sync

Command:
 
```
t3-sync
```

Options:
 
```
=======================
T3 Sync - Please Select
=======================
1) Sync Develop (DB and Files)
2) Sync Develop (DB only)
3) Get  Develop (DB as File)
4) Sync Master (DB and Files)
5) Sync Master (DB only)
6) Get  Master (DB as File)
7) Quit
```
