## Sisense garbage collector of logs


Garbage collector tool provides the ability to delete unnecessary logs history that consume a lot of disk space from  Sisense directories.


Steps:

1. Download this repository with zip option to your Sisense server.
2. Unzip the file.
3. Open dir path configuration file ("dir_paths.ini") 
4. Update your logs directory path that you want to delete and number of history logs you want to save.
![example](https://user-images.githubusercontent.com/7319365/29242169-92b07364-7f90-11e7-8067-f24cdc433e48.png)
5. Set up the trigger as it fit to your flow (For example windows task schedule every day) with executing "garbage_collector.exe" as admin.

