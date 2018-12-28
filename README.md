# Create-TreeSizeHtml
A Powershell clone of the classic TreeSize administrators tool



#### CREDIT
[James Weakley](https://github.com/jamesweakley/TreeSizeHtml)

[Chris Taylor](https://github.com/ChrisTaylorRocks/TreeSizeHtml)

[Gavin Stone](https://github.com/gavsto)




## EXAMPLE

```
PS C:\WINDOWS\system32> (new-object Net.WebClient).DownloadString('http://bit.ly/TREESIZEHTML') | iex;
PS C:\WINDOWS\system32> Create-TreeSizeHtml -paths 'c:\install' -reportOutputFolder 'c:\install' -htmlOutputFilenames 'DiskReport-C_Install'

```
