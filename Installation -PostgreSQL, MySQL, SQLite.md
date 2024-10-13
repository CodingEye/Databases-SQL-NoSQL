## Installation Guide

To get started with SQL, you need to install a relational database management system (RDBMS) on your computer. Here are the installation instructions for the most popular RDBMS:

### MySQL

1. Visit the official MySQL website at [https://dev.mysql.com/downloads/installer/](https://dev.mysql.com/downloads/installer/).
2. Download the MySQL Installer for your operating system.
3. Run the installer and follow the on-screen instructions.
4. During the installation, select the "MySQL Server" component.
5. Choose the appropriate setup type (e.g., Developer Default or Server Only).
6. Set a root password for the MySQL Server.
7. Complete the installation process.
8. Verify the installation by opening a command prompt and running the following command:
   
```
mysql --version
```
   
You should see the installed MySQL version printed on the console.

### PostgreSQL

1. Go to the official PostgreSQL website at [https://www.postgresql.org/download/](https://www.postgresql.org/download/).
2. Choose your operating system and download the PostgreSQL installer.
3. Run the installer and follow the on-screen instructions.
4. During the installation, select the components you want to install, including the PostgreSQL Server and command-line tools.
5. Choose the installation directory and port number (the default values are usually fine).
6. Set a password for the PostgreSQL superuser (postgres).
7. Complete the installation process.
8. Verify the installation by opening a command prompt and running the following command:
   
```
psql --version
```
   
You should see the installed PostgreSQL version printed on the console.

### SQLite

1. Visit the official SQLite website at [https://www.sqlite.org/download.html](https://www.sqlite.org/download.html).
2. Download the precompiled binaries for your operating system.
3. Extract the downloaded file to a directory of your choice.
4. Add the directory containing the SQLite binary to your system's PATH environment variable.
5. Verify the installation by opening a command prompt and running the following command:
   
```
sqlite3 --version
```
   
You should see the installed SQLite version printed on the console.

Choose the RDBMS that best suits your needs and follow the corresponding installation instructions. Once you have successfully installed an RDBMS, you can proceed with the SQL lessons and exercises provided in this repository.