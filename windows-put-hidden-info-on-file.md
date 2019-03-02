# Hide info on a file using ADS

To hide information in a file run: `notepad file-name:ADS-name`

Example with this file: `notepad hidden_info_on_file.txt:hiddeninfo`

Re-run the command to show the hidden information.

**Note**: Alternate Data Stream (ADS) is supported only on NTFS file system. If the file is copied or moved to a different file system, such as FAT32, all the ADS information will be dropped and the hidden information will be lost.