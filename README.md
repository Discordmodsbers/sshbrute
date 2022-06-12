# sshbrute

sshbrute provides: a modified txt file for dictionary attack
usage: sshbrute.py [-h] [-P PASSLIST] [-u USER] host

SSH Brute Python script.

positional arguments:
  host                  Hostname or IP Address of SSH Server to bruteforce.

optional arguments:
  -h, --help            show this help message and exit
  -P PASSLIST, --passlist PASSLIST
                        File that contain password list in each line.
  -u USER, --user USER  Host username.
```
pip install -r requirments.txt
```
```
git clone https://github.com/Discordmodsbers/sshbrute
cd sshbrute
python3 sshbrute.py -h
```
