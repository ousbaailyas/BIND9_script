# BIND9

BIND is a suite of software for interacting with the Domain Name System. Its most prominent component, named, performs both of the main DNS server roles, acting as an authoritative name server for DNS zones and as a recursive resolver in the network.
it was initially released in 2000 and is regularly maintained by the Internet Systems Consortium.

# BIND9_script
A simple script to setup and manage bind9 tool.
> Note: tested on Ubuntu

## Usage 
```
sudo git clone https://github.com/ousbaailyas/BIND9_script.git
```
```
cd BIND_script
```
```
chmod +x bind_installer
```
```
./bind_installer
```
## Or you can export it to the PATH environmental variable

> PATH is an environmental variable in Linux and other Unix-like operating systems that tells the shell which directories to search for executable files (i.e., ready-to-run programs) in response to commands issued by a user.

```
sudo echo "$PATH"
```
usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin

```
sudo mv bind_installer /<sbin or any path you like>
```
```
sudo bind_installer
```

![alt text](https://github.com/ousbaailyas/BIND9_script/blob/master/Screen%20Shot%202022-02-20%20at%2010.55.51%20PM.png)

# :)
