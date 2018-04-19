# oracle_online_backup_manager
Master script to install or verify child scripts on a server to execute an online backup of an oracle DB

I'm a lazy system engineer so I created this script to install and check local scripts to execute an online backup of oracle DBs.
This script relays on a central backup software (in our case is networker). So when the central backup software is starting the backup of the files of the system, we execute the begin backup on the DB. The central backup software that we use has the ability to execute a script before starting the backup and after the backup. So we use this scripts to make all the necessary on the database.
