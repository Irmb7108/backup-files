Backup Script
A Bash script for backing up directories and files, which creates backup folders with timestamps and copies the requested files.

Prerequisites
Before running this script, make sure that you have the following packages installed:

lolcat
git
If any of these packages is missing, the scripts prompts you to install them.

Usage
Clone the repository to your desired directory using git:
Copy
Insert
New
$ git clone https://github.com/{username}/{repository}.git 
Open the cloned repository directory:
Copy
Insert
New
$ cd {repository}
Run the script:
Copy
Insert
New
$ ./bg.sh 
Follow the instructions that appear on the screen.
Features
If a necessary package is not found, the script asks if you would like to install it.
Creates a directory with timestamps and copies backup files there.
Copies only backup files into the created directory.
Shows the progress of copying files through an animated spinner.
Writes the backup information to backup_$(date "+%H-%M-%S").md file.
Dependencies
This script requires the following packages to be installed:

lolcat
git
Credits
Created by IR-MB.

Backup Image

To add an image to your README file, you can use an image hosting service like Imgur or Cloudinary, and obtain a public link for the image. Then, you can use Markdown syntax to include the image in your file:

Copy
Insert
New
![alt text](https://s2.uupload.ir/files/screenshot_20230313_004422_7jsq.png)
