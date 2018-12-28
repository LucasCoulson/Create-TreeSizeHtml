# Create-TreeSizeHtml
A Powershell clone of the classic TreeSize administrators tool



#### CREDIT
[James Weakley](https://github.com/jamesweakley/TreeSizeHtml)

[Chris Taylor](https://github.com/ChrisTaylorRocks/TreeSizeHtml)

[Gavin Stone](https://github.com/gavsto)

[Lucas Coulson](https://github.com/LucasCoulson/Create-TreeSizeHtml)



## EXAMPLE
##### Call From GitHub
>(new-object Net.WebClient).DownloadString('http://bit.ly/TREESIZEHTML') | iex;

```
PS C:\WINDOWS\system32> (new-object Net.WebClient).DownloadString('http://bit.ly/TREESIZEHTML') | iex;
PS C:\WINDOWS\system32> Create-TreeSizeHtml -paths 'c:\install' -reportOutputFolder 'c:\install' -htmlOutputFilenames 'DiskReport-C_Install'

Report Parameters
-----------------
Locations to include:
- c:\install to c:\install\DiskReport-C_Install

Filters:
- Displaying largest 10 files per folder
- After a depth of 2 folders, branches with a total size less than 100.00 MB are excluded

Build Status
-----------------
Building object tree for path c:\install
Building HTML output
Writing HTML to file c:\install\DiskReport-C_Install.html
Skipping zip file creation
```
## EXAMPLE OUTPUT

##### Logo optional. Encode logo here [HERE](https://www.base64-image.de/)

![alt text](https://github.com/LucasCoulson/Create-TreeSizeHtml/blob/master/example.PNG?raw=true)
