# Observer Script

This repository contains two files that work together to create a file system observer, which logs changes to a specified directory.

## Files

1. `observer_script.bat`: Batch file that triggers the execution of the Python script.
2. `observer_script.py`: Python script that sets up and starts the observer, logging the events to a log file.

## Usage

To use this observer script, simply execute the batch file, providing the directory you want to observe as an argument.

observer_script.bat <path_to_directory>

This will start the observer, and any changes to the specified directory will be logged in the log.txt file.
