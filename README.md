# FLO-blockchain

SETTING UP FLO WALLET IN LINUX
press enter after you write each command for the action
1.Check version (it should be 16.04 or more)
 command to check version –  lsb_release -a
if you need to update update using  sudo apt-get update command
upgrade s/w using sudo apt-get upgrade command

2.Download flo wallet
https://flo.cash 
it is a 22.9 mb file
extract it you find two folders-bin and share
bin contains all the binaries for flo walet

3.start flo-qt file
flo-qt –: qt desktop variant of the flo wallet
flod – flo demon i.e headlist version of the flo wallet
it means you will not see its ui but u can use its functionalities
for these functionality to access you will need flo-cli i.e flo command line interface to access all the commands running on flod
other two files rae not generally used

for these wallet to start open terminal
go to the folder having flo extracted

In my case it is inside ranchimall folder inside Document folder
cd Document
cd ranchimall
cd flo and enter tab uget the entire folder name then enter

now for opening files
./flo-qt command
Flo wallet opens
u can choose default or custom directory 
it will take time to downloadbased on internet speed (5-6 hrs)
5yrs35 weeks behind
u can speed up by downloading rar file from drive and then copying the whole in .flo directrory created in home or in your target directory(if you have hosn your directory
https://drive.google.com/file/d/1EacN9-yIZwoJhJrq3SdUUYLocHyr4hkI/view


after downloading and extracting this folder copy it’s contents to the target folder for flo
close flo wallet and restart it
a dialog apperas and it will ask for reindexing ,click ok and you are done let it reindex.
Reindexing takes about 6-7 hours to 1 day based on your internet speed.


Default directory for downloading flo-qt data- home/username/.flo
see hidden files in home directory using ctrl + h

General Linux instructions:-
to go to previous directory  use cd .. command
to display all files in a directory use command ls command
cd documents

cd Documents
ls
--> displays ranchimall
cd ranchimall
 ls
--> dispalys 'chat message ranchi mall for instructions.odt'  'TASKS LIST RANCHI MALL.odt'
 flo-0.15.1
 cd flo-0.15.1/
 ls
--> displays bin  share
cd bin
 ls
--> displays flo-cli  flod  flo-qt  flo-tx  test_flo
 ./flo-qt










