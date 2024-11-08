copy this folder (splunk_user_profile)
copy libs folder (Deployment/libs)

upload both folders to splunk users home

for example: 
my splunk user (user under which I'm runnin splunk) is svc_splunk, hence his home is: /home/svc_splunk
so I will libs and splunk_user_profile under /home/svc_splunk those folders there:
[splunk@testSplunk ~]$ ls -a
.  ..  .bash_logout  .bash_profile  .bashrc  .config  libs  .splunk  splunk_user_profile

Append below line
. ~/splunk_user_profile/.user_profile
. ~/splunk_user_profile/.splunk_profile

to .bash_profile or if not exist then to .profile

Switch on line numbering in vim/vi
==================================
cp ~/splunk_user_profile/.vimrc ~


Switch on line numbering in SPL Editor
======================================

mkdir $SPLUNK_HOME/etc/apps/user-prefs/local/
cat >> $SPLUNK_HOME/etc/apps/user-prefs/local/user-prefs.conf <<EOF
[general]
search_line_numbers = true
EOF

splunk restart