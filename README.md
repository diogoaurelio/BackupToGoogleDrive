BackupToGoogleDrive
===================


This is a simple Python script that backups up everything that is in existing directory level and above to a Google Drive Account. 

Note: this script is work in progress, and is based on the following example:
https://code.google.com/p/gdata-python-client/source/browse/samples/docs/docs_example.py

Summary notes
=====================
This script is intended to be a quick way to copy existing Office files into an existing Google Drive acocunt, and automatically converting the files into Google Docs format. Please note that this will must certainly damage any files that have scripts associated, such as Macros, for example.
It logs the events to a backup_log.txt file for later traceability purposes.
It also reads credentials from environment.yml file.
Please note that this script was adapted from the example script given for a specific task, and is NOT be any means a proper Backup strategy. 

Execution Environment
=====================

Please add backup_log.txt file to the same directory where your backup_script.py is located, as well as the environment.yml file with proper credentials of the account where to you want to copy files.

Future Improvements
=====================
Add proper commenting, automatically create log file, add proper Error handling.