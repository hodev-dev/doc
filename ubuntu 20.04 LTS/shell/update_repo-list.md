# update ubuntu repo list 

## backup
```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.backup
```

## for change 
1- s/http:\/\/ (search)
2- /http:\/\/ir./g (replace)
```
sudo sed  's/http:\/\//http:\/\/ir./g' /etc/apt/sources.list
```
## -i replace file
```
sudo -i sed  's/http:\/\//http:\/\/ir./g' /etc/apt/sources.list
```