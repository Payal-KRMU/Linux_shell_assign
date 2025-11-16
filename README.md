# Linux_shell_assign
Linux Shell Assignment
Project Overview
This project demonstrates practical implementation of Linux shell commands and scripting for automation tasks. It includes a collection of shell scripts that perform common system administration tasks such as directory backup, system monitoring, and automated file downloads. The project serves as a hands-on learning experience for Linux environment setup, command-line proficiency, and shell scripting fundamentals.

#Instructions for Running the Scripts

#Prerequisites
 *Ubuntu Linux environment (WSL, VirtualBox, or native installation)
 *Basic shell commands accessibility
 *Internet connection (for download script)

#Setup Steps
1.Clone this repository or download the script files
2.Ensure all scripts have execute permissions:

    #bash
    *chmod +x *.sh
     Run scripts individually as needed

    # Running the Scripts
    
    1. For Backup Script:
       ./backup_directory.sh
    2. System Monitor Script:
       ./system_monitor.sh
    3. Auto Downloader Script:
       ./auto_downloader.sh


# Notes
* Some scripts may require modification of directory paths before execution
* The system monitor script creates a log file in the same directory
* Ensure adequate disk space for backup operations

# Brief Description of Each Script
1. backup_directory.sh
* Purpose: Creates timestamped backups of specified directories
* Functionality:
 1.Automatically generates backup folders with current date and time         
 2.Copies entire directory structure to backup location
 3.Provides success/failure status messages

2. system_monitor.sh
* Purpose: Monitors and logs system resource usage
* Functionality:
  1.Tracks CPU and memory utilization at regular intervals
  2.Logs data to a file with timestamps
  3.Useful for performance analysis and troubleshooting

3. auto_downloader.sh
* Purpose: Automates file downloads from the internet
* Functionality:
  1.Downloads files from specified URLs using wget
  2.Saves files to predefined directories
  3.Includes error handling for network issues

## Features
* Clean and readable code with proper comments
* Error handling and status reporting
* Configurable parameters for flexibility
* Educational value for Linux beginners

## Learning Outcomes
   This project helps develop:
    * Linux command-line proficiency
    * Shell scripting skills
    * System administration basics
    * Automation techniques
    * Problem-solving in Linux environments
