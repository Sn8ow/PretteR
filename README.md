# <h1 align="center">PretteR</h1>
<h1 align="left">Hacking/Control Windows</h1>


# Downloading
```
Open Terminal (Preferably as ROOT)
git clone https://github.com/Sn8ow/PretteR/
cd PretteR
chmod 777 * 
./pretter.sh 
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

# Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/Be3De3Me4"><img src="https://avatars.githubusercontent.com/u/81803305?v=4" width="100px;" alt=""/><br /><sub><b>Be3De3Me4</b></sub></a><br /><a href="#question-kentcdodds" </a> <a href="https://github.com/Sn8ow/YouTubeBotter/graphs/contributors" </a> 
      <td align="center<tr>
    <td align="center"><a href="https://github.com/Sn8ow"><img src="https://avatars.githubusercontent.com/u/80784394?v=4" width="100px;" alt=""/><br /><sub><b>Sn_8ow</b></sub></a><br /><a <a href="https://discord.gg/TR5XDAAef5" title="Discord">🤖</a> </a> <a href="https://github.com/Sn8ow/YouTubeBotter/graphs/contributors" </a> 
