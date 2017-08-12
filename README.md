## Sisense garbage collector of logs


Garbage collector tool provides the ability to delete unnecessary logs history that consume a lot of disk space from  Sisense directories.


Steps:

1. Download this repository with zip option to your Sisense server.
2. Unzip the file.
3. Open dir path configuration file ("dir_paths.ini") 
4. Update your logs directory path that you want to delete and number of history logs you want to save.
5. Set up the trigger as it fit to your flow (For example windows task schedule every day).

