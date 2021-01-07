1> sudo # Run as Adminstrator
2> sudo su # su= Switch user(not to use in prod)
3> exit
4> clear
5> man clear (manual about clear) > to get out of this press "q"
6> mkdir saurav # to create folder
7> cd saurav # change directory 
8> cd .. # back to previous folder
9> rmdir saurav # delete folder
10> pwd # present working directory
11> touch myfile # create file
12> ls # folder and files in current directory
13> locate myfile # how can we find files on a linux system
14> sudo updatedb #locate data userbase, it will update all the indexes(all the files in the system)
15> mv # move files to diffrent folder eg: "mv myfile Desktop/"
16> mv # it is used for renaming  eg: "mv myfile changedfile"
17> rm # delete file
18> rm -R -f / # remove recursive and forcefully delete everything and never run this command as sudo & (/)
               # '/' represents entire linux file system . In Windows it's equivalent to C:/
19> cp # copy file. eg: cp myfile Desktop/ > ls Desktop/
20> cat # getting content out of the file, this is short form of concatenate. eg: cat myfile.
21> echo # add content to the file eg: echo "hello"
                                       echo "hello" > myfile 
                                       cat myfile (it will now display :"hello")

                                       echo "hello world" > myfile 
                                       cat myfile (it will now display :"hello world")

                                       echo "From Saurav" >> myfile 
                                       cat myfile (it will now display :"hello world"
                                                                         From Linux )

22> grep # pipes it eg: cat myfile | grep Hello
23> history # to get all the linux commands.
24> history -c # it clears everything.
