# Coding Conventions [![Repo Size](https://reposs.herokuapp.com/?path=pjkaufman/Coding_conventions)](https://github.com/pjkaufman/Coding_conventions)  [![Current Issues](https://img.shields.io/github/issues/pjkaufman/Coding_conventions.svg)](https://github.com/pjkaufman/Coding_conventions/issues)  [![License](https://img.shields.io/github/license/pjkaufman/Coding_conventions.svg)](https://github.com/pjkaufman/Coding_conventions/blob/master/LICENSE)
###### By Peter Kaufman
This repo is where I am putting my coding conventions for anyone that might like to contribute to any of my repositories.
## To Edit the Phar File
-Go to Command Line or Command Prompt  
-Edit and run the following command:

``"path-to-php.exe-file \php.exe" "path-to-php.exe-file\executable-phar-file extract -f "path-to-phar-file-to-extract" "path-where-to-put-the-extracted-folder"``

-When you are done, then run this code to setup the .phar file:  

``"path-to-php.exe-file \php.exe" "path-to-php.exe-file\executable-phar-file pack -f "path-to-phar-file-to-pack" "folder-that-contains-all-of-the-extracted-library"``
## PHP
### Setup
#### Atom Plugins
-Download the the phar file
-Copy path to the php-cs-fixer-v2.phar file and put that in the phar-cs-fixer setting.  
-Copy path to php executable in the php setting  
#### Visual Studio Code Plugins
-Download the the phar file
-Copy path to the php-cs-fixer-v2.phar file and put that in the phar-cs-fixer setting.  