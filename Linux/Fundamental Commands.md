Linux Fundamental commands:-

Echo command:-
**"echo"** simply repeats what you tell it to do:

**echo "Hello World"** 
_Hello World_

The quotes tell **"echo"** precisely what to repeat

Whoami command:-
**"whoami"** command is basically who the computer thinks you are

**whoami**
_ark_, or who you are logged in as

This is useful when you are using different machines:

Id command:-
**id** command is a way to get user information 
In Linux users are organised into groups, these identify the permissions that the user has and what they can do 

**id**
_uid=5000(ark) gid=5000(ark) groups=5000(ark),27(sudo),121(ssl-cert),5002(public)_

**uid**: Your User ID 
**gid**: Your main Group ID
**groups**: All the groups you are a member of

You can also use **id** to look up other users 

Example:-
**id root**
_uid=0(root) gid=0(root) groups=0(root)_
