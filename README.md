# Apple2jsBackup backup script (1.0.0)
Creates a backup of your Apple2js web folder

Official support sites: [Official Github Repo](https://github.com/fstltna/Apple2js-Backup) - [Official Forum](https://appleii.retro-os.live/index.php/downloads/category/23-our-server-tools)  - [Official Download Area](https://appleii.retro-os.live/index.php/downloads/category/23-our-server-tools)

---

1. Edit the settings at the top of apple2jsbackup.pl if needed
2. create a cron job like this:

        1 1 * * * /home/apple2/Apple2js-Backup/apple2jsbackup.pl

3. This will back up your Apple2js installation at 1:01am each day, and keep the last 5 backups.

4. This assumes that backupninja is storing the daily backups to /home/apple2/backups.

5. Edit the backup config:
 	Run a manual backup and it will ask you for the mysql config info. If you need to reconfigure it use the "-prefs" command-line option

If you need more help visit 
