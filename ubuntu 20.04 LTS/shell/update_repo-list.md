# update ubuntu repo list 

## backup
```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.backup
```

## for change 
- ```s/http:\/\/``` search for match
- ```/http:\/\/ir./g``` replace match with
```
sudo sed  's/http:\/\//http:\/\/ir./g' /etc/apt/sources.list
```
## -i change file without -i nothign change only show result
```
sudo -i sed  's/http:\/\//http:\/\/ir./g' /etc/apt/sources.list
```