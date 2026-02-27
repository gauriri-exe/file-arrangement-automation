# FileArrange: An Automated Directory Organizer  
A highly effective Python-based program intended to reduce disorganization in directories through intelligent file categorization according to their signatures.

##  Tech Stack:  
Language: Python 3.x (Standard Libraries)

### os  
Utilized for directory management, path joining, and metadata checks.

### shutil  
Used for high-level file management, including moving files in the file system.

## Key Features: 
### Multi-category sorting:-
Automates the categorization of files according to 10 categories, including special file types such as Adobe presets and Rainmeter skins.

### On-the-fly Directory Provision:-
Script checks for the availability of destination directories such as '/Music,' '/Documents,' etc., and creates the directories if they do not exist.

### Recursive Extension Mapping:-
Utilizes dictionary-to-list mapping for the management of multiple extensions such as '.jpg' and '.jpeg,' ensuring they fall in the same category.

### Interactive Path Input:-
Allows the user to input any path at runtime, making the script highly versatile for use in the 'Downloads,' 'Desktop,' or any other directories.


## Highlights:

### Efficient Loop Termination:-
Once the file is matched with the respective extension and moved, the script terminates the unnecessary loops using the break command.

### High Compatibility:-
The dictionary includes modern web file formats such as .webm, as well as development-related files such as .msi (NodeJs).

### Real-time Feedback:- 
It provides console logs for every file moved, giving the user an immediate audit log of the reorganization.

## How It Works:

### Initialize:- 
It initializes the script with a predefined list of categories and extensions.

### Scan:-
It scans every file in the path provided by the user.

### Match:- 
It matches the file extensions with the extensions in the library.

### Execute:- 
It moves the files if the match is found, ensuring the destination folder is created.
