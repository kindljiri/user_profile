# User profile

It is collection of shell functions and aliases which help you to do some work under linux command line easier and faster.
For example wor with certain data formats like CSV or INI

## Installation

copy this folder (user_profile) to your home
```
git clone https://github.com/kindljiri/user_profile.git
```

for example: 
my user is jkindl, hence his home is: /home/jkindl
so I will copy libs and user_profile under /home/jkindl those folders there:

```
[jkindl@testSplunk ~]$ ls -a
.  ..  .bash_logout  .bash_profile  .bashrc  .config  libs  user_profile
```

Append below line
```
. ~/user_profile/.user_profile
```

to .bash_profile or if not exist then to .profile

Switch on line numbering in vim/vi
```
cp ~/splunk_user_profile/.vimrc ~
```
