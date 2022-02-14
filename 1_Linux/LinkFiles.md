#Link Files

There are two types of link files
	- Soft link and
	- Hard link

###Soft link:

* It is a shortcut file.
* Size of the link file is equal to number of characters in the name of original file.
* If original file is deleted, link is broken and data is lost.
```
ln -s <src_file> <dest_file>
```

###Hard link:

* It is a backup file.
* Size of both file is same.
* If original file is deleted then also link will contain data.
```
ln <src_file> <dest_file>
```