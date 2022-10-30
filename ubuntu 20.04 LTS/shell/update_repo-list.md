# update ubuntu repo list 

backup
```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.backup
```

for change
```
sudo sed  's/http:\/\//http:\/\/ir./g' /etc/apt/sources.list
```
-i replace file
```
sudo -i sed  's/http:\/\//http:\/\/ir./g' /etc/apt/sources.list
```