# postgres-sample-db-dvdrental

This is a backup file of PostgreSQL sample database 'dvdrental', which can be restored and used for demonstration, tutorial, testing etc.

Setup:
-----------------------
For setting up the sample database, follow the below steps-

1. Download the backup file from Git repository.

2. Create an empty database named 'dvdrental'.

```sh
$ createdb dvdrental
```
   
   
3. Restore the backup file.

```sh
$ pg_restore -d dvdrental <file-path>/dvdrental_backup.tar
```
   
