# Ubuntu-Linux

# Install app with apt
```
sudo apt install app-name
```

#
## To verify the machine type, run the following command:
```
uname -a
```

## Update
```
sudo apt-get update
```

## Upgrade
```
sudo apt-get upgrade
```

## List the files in the current directory
```
ls
```

## List the files detail in the current directory
```
ls -l
```
## List all files (include hidden files) in the current directory
```
ls -a
```
## List all files (include subfiles) in the current directory
```
ls -R
```
## Create new folder
```
mkdir new-folder
```
## Create multiple nested folders
```
mkdir new-folder/new-folder1/new-folder2 -p
```
## Delete a folder
```
rmdir folder-name
```
## Delete a folder and subfolder
```
rm -r folder-name
```
## Create a file
```
touch fileName
```
## Delete a file
```
rm fileName
```
# Cat
## Show the contents of the file
```
cat fileName
```

# Grep
## Find in file
```
cat fileName | grep "name"
```
```
grep "name"
```

# cp - Copy
## Copy file
```
cp fileA fileB
```
## Copy folder
```
cp -r newFolderA newFolderB
```
# mv - move
## Move file
```
mv fileA FolderB
```