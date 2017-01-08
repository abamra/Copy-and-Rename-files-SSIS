# Copy-and-Rename-files-SSIS

### Description - 

The C# file/code is used to copy only the modified files from one folder to another and rename them with the date it got copied on.

### Installation -

1. The script can be copy pasted in a Script Task in SQL Server Intergration Services(SSIS).
2. Three parameters need to be setup in the Script Task -
   * SourceFolder -  Folder where the initial files are at
   * DestinationFolder - Folder where the new files need to be copied to
   * LastLoadDate- Modified date of the files in the SourceFolder -  so that only the new files are overwritten in the new folder.
