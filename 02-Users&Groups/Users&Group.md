1> passwd > Old Password > New Password # For Changing Password
2>  sudo useradd rudransh # always run as sudo
3>  sudo groupadd kubernetes 
4>  sudo usermod -a -G kubernetes rudransh # mod=modified 
5>  usermod -a -G sudo rudransh # add user to sudouser


**************************************************************
                    CRUD Permission on file 
**************************************************************
0.None                     : ---
1.Execute only             : --x
2.Write only               : -w-
3.Write and Execute        : -wx
4.Read Only                : r--
5.Read and Execute         : r-x
6.Read and Write           : rw-
7.Read,Write and Execute   : rwx 

> 
  7      7       5
User   Group  Everyone

Current permission on any file:
ls -al myfile
rw- r-- r--(User has Read & Write, Group has read, and everyone has read permission)

# chane permission
chmod  764 myfile
ls -al myfile
rwx rww- r--

chmod 760 myfile
rwx rww- ---

# Change Owner:

sudo chown root myfile
ls -al myfile
user changes to root
