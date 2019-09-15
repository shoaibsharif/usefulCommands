# usefulCommands
I am going to write down some useful commands that I may forget because I am not going to use them a lot and I don't want to forget

## Delete node_modules from any subfolders
 - On windows
 ```powershell
  get-childitem -path .\*\* -recurse -filter *node_modules* | remove-item -force -recurse
 ```
- On unix
```bash
rm -rf `find -name node_modules`
```

## Show specific extension files from a specifix
 
- On unix
```bash
find **/public/ -name "*.html" -print
```
