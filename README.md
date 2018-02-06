# Ubuntu repo

```
wget -qO - http://teseyko.com/ubuntu/PUBLIC.KEY | apt-key add -
echo "deb [arch=amd64] http://teseyko.com/ubuntu ubuntu main" > /etc/apt/sources.list.d/teseyko.list
apt update
```
