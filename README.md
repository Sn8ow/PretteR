# PretteR
Hacking/Control Windows


# Downloading
```
Open Terminal
git clone https://github.com/Sn8ow/PretteR/
cd PretteR
chmod 777 * (ROOT)
./pretter.sh (ROOT OPEN)
Finish
```


# Errors
 Check script dependencies =  【Fail】
 mono          【!!】 Not Found, first must be installed mono 
 mcs           【!!】 Not Found, first must be installed mono
 This script require all dependencies to work, install not found programs
 More information:
 https://www.metasploit.com/
 http://www.mono-project.com/
 https://www.postgresql.org/
 Exiting....
 
 # FIX
 In Terminal: apt-get install mono-devel 
 # Fix E: Could not get mono-devel package
```
echo "deb https://d2nlctn12v279m.cloudfront.net/repo/mono/ubuntu bionic main" | tee /etc/apt/sources.list.d/mono-extra.list  

apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys CB2DE8E5

apt-get update
```
