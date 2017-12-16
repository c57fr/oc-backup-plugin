# Backup system for October CMS
- [Overview](#introduction)
- [Features](#features)
- [Usage](#usage)
<a name="introduction"></a>
## Introduction
This plugin let you create backups of your files and databases. It uses the amazing laravel package [spatie/laravel-backup](https://github.com/spatie/laravel-backup).
<a name="features"></a>
## Features
- With just a click you can:
    - Create backups of the whole application.
    - Create backups of the database only.
    - Create backups of the files only.    
- Support various Database Driver (MySQL, PostgreSQL, SQLite and Mongo).
- You can easily include and exclude some files using the UI.
- Support gzip to reduce the database size.
<a name="usage"></a>
## Usage
1. To configure the backup system navigate to the `Settings > System > Backup`.
2. You can navigate to the backup section from the top main menu. From there you can create and download your backups.

Also you can create backups from the command line using `Artisan`.
![image](https://raw.githubusercontent.com/panakour/oc-backup-plugin/master/docs/images/oc_backups.png)
![image](https://raw.githubusercontent.com/panakour/oc-backup-plugin/master/docs/images/oc_backup_config.png)
![image](https://raw.githubusercontent.com/panakour/oc-backup-plugin/master/docs/images/oc_backup_config_1.png)