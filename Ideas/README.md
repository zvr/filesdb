# Ideas for this project 

## Informations per file:
* name 
* size
* full path 
* hashes 
* basename
* extension
* dirname
* permissions
* creator
* dates(creation, last modification, last access)

## Commands
### Basic commands
  * Print available commands <br />
  -> Command: h or help

  * Print (size, full path, hash, basename, dirname, permissions, creator, dates) of given file. <br />
  -> Command: psf|filename|type or print single file|filename|type
  
  * Print version <br/>
  -> Command: v or version
  
  * Scan a specific location. Read files and store informations <br />
  -> Command: scan|location or sc|location
  
  * Delete file from the database <br />
  -> Command: delete|filename or d|filename
  
### Advance commands 
   * Print all files or print x files. Last argument isn't necessary. Only usefull informations will be printed <br />
   -> Command: print all files|count or paf|count 
   
   * Print file with x size(more,less,equal). Type will be 1, 2,3  or more,less,equal <br />
   -> Command: print file size|size|type or pfs|size|type
   
   * Print files in the same directory <br />
   -> Command: pfd|directory or print files directory|directory
   
   * Print files with same extensions etc. Type will be creator, hashes etc. <br />
   -> Command: pfe|type|arguments or print files extension|type|arguments <br />
   Example: Print all files from the same director. Command will be: pfe|creator|nikos
  
## Notes
1. Commands should work with upper or lower case input


<!---
Αρχικά έχουμε διάφορα αρχεία και θέλουμε να μπορούμε να εξάγουμε διάφορες πληροφορίες από αυτά τα αρχεία και να αποθηκεύουμε σε μια βάση 
τα αποτελέσματα.
-->
  
  
  


