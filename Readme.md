#About#
> An automatic MySql table dumper and FTP Session creater for windows.

##Pre-requisites:##
- Filezilla
- 7zip
- MySql server

##Content##
To start with, there are two files available to use.

- DatabaseDump.txt
- FTPCreate.txt

DatabaseDump is the tidy command-line tool used to dump a MySQL table from the schema. This script is based on user input, however you can remove that rather simply by calling the variable to dump, rather than waiting through the prompts.

FTPCreate is an automated script which will create an FTP session, build the file list to upload, then commit the changes.

Again, these files require user changes to work. For quick reference the changes are the areas within dollar tags IE = $text$

To get started, simply rename the script you wish to use with the .bat extension and edit the file to input your required information. 
