copy this folder (user_profile) to your home
copy libs folder (libs) to your home

for example: 
my user is jkindl, hence his home is: /home/jkindl
so I will copy libs and user_profile under /home/jkindl those folders there:
[jkindl@testSplunk ~]$ ls -a
.  ..  .bash_logout  .bash_profile  .bashrc  .config  libs  user_profile

Append below line
. ~/user_profile/.user_profile

to .bash_profile or if not exist then to .profile

Switch on line numbering in vim/vi
cp ~/splunk_user_profile/.vimrc ~
