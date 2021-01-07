# Linux is made up of configuration file(folders and files)
# In Windows "C:/" is root & in Linux it's forward "/"

> "cd /" = this will take us to root
>ls

1> dev > Stores special file & represents disk and storage on our system:

         /dev/sda    (storage disk a, main hard drive)
         /dev/random (produces random numbers).
         /dev/null    (if we don't want to store anything after execution)


2> etc > This is where Linux Configuration files are stored.If we want to do some changes in the system, it's in this folder.
          nsswitch.conf, usb_modeswitch.conf etc.


3> home > Tgis is the place where "Users" folder are stored
           cd ~ (takes directly to home folder)


4> lib > Common resousers and can be shared to different tools.
            apt-get update/install

5> media > moveable devices get added


6> mnt > Nothing there, it's temporary mounting point.


7> opt > directory for optional software packages.


8> proc > Stores Kernel Information & info about running process (Windows: services.msc)
         cat cpuinfo


9> root > same as /home/usrname but for root users
          cd root/ : Permission Denied
          sudo su > cd root/ > ls(nothing there)
          exit

10> sbin > Same as /bin except it is for su(super user). For root user.


11> run > place holder directory for application state(app stores its information)


12> usr > Key binaries(what user has install(docker))
          usr/local

   
13> boot > Contains all the file that system needs to boot.

14> var > 
          application stores in /usr/bin(read file)
          /var writeable counterpart (write )> /var/logs

15> tmp > This is place of disk where we can store temporary files.If machine restart these files will get deleted.

16> bin > all executables and binaries stored here