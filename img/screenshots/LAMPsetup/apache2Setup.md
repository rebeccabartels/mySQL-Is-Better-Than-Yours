<pre><font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ cd 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~</b></font>$ ls
<font color="#729FCF"><b>Desktop</b></font>      <font color="#729FCF"><b>Documents</b></font>  examples.desktop  <font color="#729FCF"><b>Pictures</b></font>  <font color="#729FCF"><b>Templates</b></font>
<font color="#729FCF"><b>Development</b></font>  <font color="#729FCF"><b>Downloads</b></font>  <font color="#729FCF"><b>Music</b></font>             <font color="#729FCF"><b>Public</b></font>    <font color="#729FCF"><b>Videos</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~</b></font>$ cd Development/
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development</b></font>$ ls
<font color="#729FCF"><b>ColumbiaCyber</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development</b></font>$ cd ColumbiaCyber/
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber</b></font>$ ls
<font color="#729FCF"><b>CU-NYC-CYBER-PT-09-2019-U-C</b></font>  <font color="#729FCF"><b>FinalProject</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber</b></font>$ cd FinalProject/
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ ls
conf.inc.php  php.ini  turnonlamp.sh
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ sudo apt install mysql-server
[sudo] password for riley: 
Sorry, try again.
[sudo] password for riley: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  efibootmgr libfwup1 libwayland-egl1-mesa
Use &apos;sudo apt autoremove&apos; to remove them.
The following additional packages will be installed:
  libaio1 libevent-core-2.1-6 libhtml-template-perl mysql-client-5.7
  mysql-client-core-5.7 mysql-common mysql-server-5.7 mysql-server-core-5.7
Suggested packages:
  libipc-sharedcache-perl mailx tinyca
The following NEW packages will be installed:
  libaio1 libevent-core-2.1-6 libhtml-template-perl mysql-client-5.7
  mysql-client-core-5.7 mysql-common mysql-server mysql-server-5.7
  mysql-server-core-5.7
0 upgraded, 9 newly installed, 0 to remove and 3 not upgraded.
Need to get 19.1 MB of archives.
After this operation, 155 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu bionic/main amd64 mysql-common all 5.8+1.0.4 [7,308 B]
Get:2 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libaio1 amd64 0.3.110-5ubuntu0.1 [6,476 B]
Get:3 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 mysql-client-core-5.7 amd64 5.7.29-0ubuntu0.18.04.1 [6,642 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 mysql-client-5.7 amd64 5.7.29-0ubuntu0.18.04.1 [1,942 kB]
Get:5 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 mysql-server-core-5.7 amd64 5.7.29-0ubuntu0.18.04.1 [7,430 kB]
Get:6 http://us.archive.ubuntu.com/ubuntu bionic/main amd64 libevent-core-2.1-6 amd64 2.1.8-stable-4build1 [85.9 kB]
Get:7 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 mysql-server-5.7 amd64 5.7.29-0ubuntu0.18.04.1 [2,933 kB]
Get:8 http://us.archive.ubuntu.com/ubuntu bionic/main amd64 libhtml-template-perl all 2.97-1 [59.0 kB]
Get:9 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 mysql-server all 5.7.29-0ubuntu0.18.04.1 [9,944 B]
Fetched 19.1 MB in 4s (4,830 kB/s)<font color="#C4A000"> </font>
Preconfiguring packages ...
Selecting previously unselected package mysql-common.
(Reading database ... 165522 files and directories currently installed.)
Preparing to unpack .../0-mysql-common_5.8+1.0.4_all.deb ...
Unpacking mysql-common (5.8+1.0.4) ...
Selecting previously unselected package libaio1:amd64.
Preparing to unpack .../1-libaio1_0.3.110-5ubuntu0.1_amd64.deb ...
Unpacking libaio1:amd64 (0.3.110-5ubuntu0.1) ...
Selecting previously unselected package mysql-client-core-5.7.
Preparing to unpack .../2-mysql-client-core-5.7_5.7.29-0ubuntu0.18.04.1_amd64.deb ...
Unpacking mysql-client-core-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Selecting previously unselected package mysql-client-5.7.
Preparing to unpack .../3-mysql-client-5.7_5.7.29-0ubuntu0.18.04.1_amd64.deb ...
Unpacking mysql-client-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Selecting previously unselected package mysql-server-core-5.7.
Preparing to unpack .../4-mysql-server-core-5.7_5.7.29-0ubuntu0.18.04.1_amd64.deb ...
Unpacking mysql-server-core-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Selecting previously unselected package libevent-core-2.1-6:amd64.
Preparing to unpack .../5-libevent-core-2.1-6_2.1.8-stable-4build1_amd64.deb ...
Unpacking libevent-core-2.1-6:amd64 (2.1.8-stable-4build1) ...
Setting up mysql-common (5.8+1.0.4) ...
update-alternatives: using /etc/mysql/my.cnf.fallback to provide /etc/mysql/my.cnf (my.cnf) in auto mode
Selecting previously unselected package mysql-server-5.7.
(Reading database ... 165690 files and directories currently installed.)
Preparing to unpack .../mysql-server-5.7_5.7.29-0ubuntu0.18.04.1_amd64.deb ...
Unpacking mysql-server-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Selecting previously unselected package libhtml-template-perl.
Preparing to unpack .../libhtml-template-perl_2.97-1_all.deb ...
Unpacking libhtml-template-perl (2.97-1) ...
Selecting previously unselected package mysql-server.
Preparing to unpack .../mysql-server_5.7.29-0ubuntu0.18.04.1_all.deb ...
Unpacking mysql-server (5.7.29-0ubuntu0.18.04.1) ...
Setting up libevent-core-2.1-6:amd64 (2.1.8-stable-4build1) ...
Setting up libhtml-template-perl (2.97-1) ...
Setting up libaio1:amd64 (0.3.110-5ubuntu0.1) ...
Setting up mysql-client-core-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Setting up mysql-server-core-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Setting up mysql-client-5.7 (5.7.29-0ubuntu0.18.04.1) ...
Setting up mysql-server-5.7 (5.7.29-0ubuntu0.18.04.1) ...
update-alternatives: using /etc/mysql/mysql.cnf to provide /etc/mysql/my.cnf (my.cnf) in auto mode
Renaming removed key_buffer and myisam-recover options (if present)
Created symlink /etc/systemd/system/multi-user.target.wants/mysql.service → /lib/systemd/system/mysql.service.
Setting up mysql-server (5.7.29-0ubuntu0.18.04.1) ...
Processing triggers for libc-bin (2.27-3ubuntu1) ...
Processing triggers for systemd (237-3ubuntu10.39) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Processing triggers for ureadahead (0.100.0-21) ...
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ mysql_secure_installation

Securing the MySQL server deployment.

Enter password for user root: 
Error: Access denied for user &apos;root&apos;@&apos;localhost&apos;
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ sudo mysql_secure_installation

Securing the MySQL server deployment.

Connecting to MySQL using a blank password.

VALIDATE PASSWORD PLUGIN can be used to test passwords
and improve security. It checks the strength of password
and allows the users to set only those passwords which are
secure enough. Would you like to setup VALIDATE PASSWORD plugin?

Press y|Y for Yes, any other key for No: y

There are three levels of password validation policy:

LOW    Length &gt;= 8
MEDIUM Length &gt;= 8, numeric, mixed case, and special characters
STRONG Length &gt;= 8, numeric, mixed case, special characters and dictionary                  file

Please enter 0 = LOW, 1 = MEDIUM and 2 = STRONG: 0
Please set the password for root here.

New password: 

Re-enter new password: 
Sorry, passwords do not match.

New password: 

Re-enter new password: 

Estimated strength of the password: 50 
Do you wish to continue with the password provided?(Press y|Y for Yes, any other key for No) : y
By default, a MySQL installation has an anonymous user,
allowing anyone to log into MySQL without having to have
a user account created for them. This is intended only for
testing, and to make the installation go a bit smoother.
You should remove them before moving into a production
environment.

Remove anonymous users? (Press y|Y for Yes, any other key for No) : y
Success.


Normally, root should only be allowed to connect from
&apos;localhost&apos;. This ensures that someone cannot guess at
the root password from the network.

Disallow root login remotely? (Press y|Y for Yes, any other key for No) : y
Success.

By default, MySQL comes with a database named &apos;test&apos; that
anyone can access. This is also intended only for testing,
and should be removed before moving into a production
environment.


Remove test database and access to it? (Press y|Y for Yes, any other key for No) : y
 - Dropping test database...
Success.

 - Removing privileges on test database...
Success.

Reloading the privilege tables will ensure that all changes
made so far will take effect immediately.

Reload privilege tables now? (Press y|Y for Yes, any other key for No) : y
Success.

All done! 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ apache

Command &apos;apache&apos; not found, did you mean:

  command &apos;apache2&apos; from deb apache2-bin

Try: sudo apt install &lt;deb name&gt;

<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ apache2
[Sat Mar 07 19:32:34.390488 2020] [core:warn] [pid 15358] AH00111: Config variable ${APACHE_RUN_DIR} is not defined
apache2: Syntax error on line 80 of /etc/apache2/apache2.conf: DefaultRuntimeDir must be a valid directory, absolute or relative to ServerRoot
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>~/Development/ColumbiaCyber/FinalProject</b></font>$ cd /etc/apache2<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ ls
apache2.conf    <font color="#729FCF"><b>conf-enabled</b></font>  magic           <font color="#729FCF"><b>mods-enabled</b></font>  <font color="#729FCF"><b>sites-available</b></font>
<font color="#729FCF"><b>conf-available</b></font>  envvars       <font color="#729FCF"><b>mods-available</b></font>  ports.conf    <font color="#729FCF"><b>sites-enabled</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ nano apache2.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ nano apache2.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ sudo nano apache2.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ source /etc/apache2/envars
bash: /etc/apache2/envars: No such file or directory
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ source /etc/apache2/envvars
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ apache2
AH00526: Syntax error on line 3 of /etc/apache2/mods-enabled/dir.conf:
Invalid command &apos;index.xhtml&apos;, perhaps misspelled or defined by a module not included in the server configuration
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ sudo nano /etc/apache2/mods-enabled/dir.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ ls
apache2.conf    <font color="#729FCF"><b>conf-enabled</b></font>  magic           <font color="#729FCF"><b>mods-enabled</b></font>  <font color="#729FCF"><b>sites-available</b></font>
<font color="#729FCF"><b>conf-available</b></font>  envvars       <font color="#729FCF"><b>mods-available</b></font>  ports.conf    <font color="#729FCF"><b>sites-enabled</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ apache2
AH00558: apache2: Could not reliably determine the server&apos;s fully qualified domain name, using 127.0.1.1. Set the &apos;ServerName&apos; directive globally to suppress this message
(13)Permission denied: AH00072: make_sock: could not bind to address [::]:80
(13)Permission denied: AH00072: make_sock: could not bind to address 0.0.0.0:80
no listening sockets available, shutting down
AH00015: Unable to open logs
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ sudo nano /etc/apache2/mods-enabled/dir.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ ls
apache2.conf    <font color="#729FCF"><b>conf-enabled</b></font>  magic           <font color="#729FCF"><b>mods-enabled</b></font>  <font color="#729FCF"><b>sites-available</b></font>
<font color="#729FCF"><b>conf-available</b></font>  envvars       <font color="#729FCF"><b>mods-available</b></font>  ports.conf    <font color="#729FCF"><b>sites-enabled</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2</b></font>$ cd mods-enabled/
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ cat dir.conf 
&lt;IfModule mod_dir.c&gt;
	DirectoryIndex index.php index.html index.cgi index.pl index.xhtml index.htm
&lt;/IfModule&gt;

# vim: syntax=apache ts=4 sw=4 sts=4 sr noet
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo nano dir.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ apache2
(13)Permission denied: AH00072: make_sock: could not bind to address [::]:80
(13)Permission denied: AH00072: make_sock: could not bind to address 0.0.0.0:80
no listening sockets available, shutting down
AH00015: Unable to open logs
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo apache2
[Sat Mar 07 19:44:59.996680 2020] [core:warn] [pid 15509] AH00111: Config variable ${APACHE_RUN_DIR} is not defined
apache2: Syntax error on line 80 of /etc/apache2/apache2.conf: DefaultRuntimeDir must be a valid directory, absolute or relative to ServerRoot
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo service apache2 restart
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ apache2
(13)Permission denied: AH00072: make_sock: could not bind to address [::]:80
(13)Permission denied: AH00072: make_sock: could not bind to address 0.0.0.0:80
no listening sockets available, shutting down
AH00015: Unable to open logs
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo apache2     
[Sat Mar 07 19:45:45.813892 2020] [core:warn] [pid 15533] AH00111: Config variable ${APACHE_RUN_DIR} is not defined
apache2: Syntax error on line 80 of /etc/apache2/apache2.conf: DefaultRuntimeDir must be a valid directory, absolute or relative to ServerRoot
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo service start apache2
start: unrecognized service
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo start apache2
sudo: start: command not found
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls          
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ cd dir.conf
bash: cd: dir.conf: Not a directory
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ cat dir.conf 
&lt;IfModule mod_dir.c&gt;
	DirectoryIndex index.php index.html index.cgi index.pl index.xhtml index.htm
&lt;/IfModule&gt;

# vim: syntax=apache ts=4 sw=4 sts=4 sr noet
ServerName 127.0.0.1
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo nano dir.conf 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo service apache2 restart
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ ls
<font color="#34E2E2"><b>access_compat.load</b></font>  <font color="#34E2E2"><b>authz_user.load</b></font>  <font color="#34E2E2"><b>filter.load</b></font>       <font color="#34E2E2"><b>php7.2.load</b></font>
<font color="#34E2E2"><b>alias.conf</b></font>          <font color="#34E2E2"><b>autoindex.conf</b></font>   <font color="#34E2E2"><b>mime.conf</b></font>         <font color="#34E2E2"><b>reqtimeout.conf</b></font>
<font color="#34E2E2"><b>alias.load</b></font>          <font color="#34E2E2"><b>autoindex.load</b></font>   <font color="#34E2E2"><b>mime.load</b></font>         <font color="#34E2E2"><b>reqtimeout.load</b></font>
<font color="#34E2E2"><b>auth_basic.load</b></font>     <font color="#34E2E2"><b>deflate.conf</b></font>     <font color="#34E2E2"><b>mpm_prefork.conf</b></font>  <font color="#34E2E2"><b>setenvif.conf</b></font>
<font color="#34E2E2"><b>authn_core.load</b></font>     <font color="#34E2E2"><b>deflate.load</b></font>     <font color="#34E2E2"><b>mpm_prefork.load</b></font>  <font color="#34E2E2"><b>setenvif.load</b></font>
<font color="#34E2E2"><b>authn_file.load</b></font>     <font color="#34E2E2"><b>dir.conf</b></font>         <font color="#34E2E2"><b>negotiation.conf</b></font>  <font color="#34E2E2"><b>status.conf</b></font>
<font color="#34E2E2"><b>authz_core.load</b></font>     <font color="#34E2E2"><b>dir.load</b></font>         <font color="#34E2E2"><b>negotiation.load</b></font>  <font color="#34E2E2"><b>status.load</b></font>
<font color="#34E2E2"><b>authz_host.load</b></font>     <font color="#34E2E2"><b>env.load</b></font>         <font color="#34E2E2"><b>php7.2.conf</b></font>
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ apache2ctl
Usage: /usr/sbin/apache2ctl start|stop|restart|graceful|graceful-stop|configtest|status|fullstatus|help
       /usr/sbin/apache2ctl &lt;apache2 args&gt;
       /usr/sbin/apache2ctl -h            (for help on &lt;apache2 args&gt;)
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ apache2ctl start
(13)Permission denied: AH00072: make_sock: could not bind to address [::]:80
(13)Permission denied: AH00072: make_sock: could not bind to address 0.0.0.0:80
no listening sockets available, shutting down
AH00015: Unable to open logs
Action &apos;start&apos; failed.
The Apache error log may have more information.
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ sudo apache2ctl start
Invoking &apos;systemctl start apache2&apos;.
Use &apos;systemctl status apache2&apos; for more info.
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/etc/apache2/mods-enabled</b></font>$ systemctl status apache2
<font color="#8AE234"><b>*</b></font> apache2.service - The Apache HTTP Server
   Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: 
  Drop-In: /lib/systemd/system/apache2.service.d
           `-apache2-systemd.conf
   Active: <font color="#8AE234"><b>active (running)</b></font> since Sat 2020-03-07 19:54:27 EST; 52s ago
  Process: 15943 ExecStop=/usr/sbin/apachectl stop (code=exited, status=0/SUCCES
  Process: 15948 ExecStart=/usr/sbin/apachectl start (code=exited, status=0/SUCC
 Main PID: 15952 (apache2)
    Tasks: 6 (limit: 4915)
   CGroup: /system.slice/apache2.service
           |-15952 /usr/sbin/apache2 -k start
           |-15953 /usr/sbin/apache2 -k start
           |-15954 /usr/sbin/apache2 -k start
           |-15955 /usr/sbin/apache2 -k start
           |-15956 /usr/sbin/apache2 -k start
           `-15957 /usr/sbin/apache2 -k start

Mar 07 19:54:27 riley-VirtualBox systemd[1]: Starting The Apache HTTP Server...
Mar 07 19:54:27 riley-VirtualBox systemd[1]: Started The Apache HTTP Server.
<span style="background-color:#D3D7CF"><font color="#2E3436">lines 1-19/19 (END)</font></span>...skipping...
<font color="#8AE234"><b>*</b></font> apache2.service - The Apache HTTP Server
   Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: enabled)
  Drop-In: /lib/systemd/system/apache2.service.d
           `-apache2-systemd.conf
   Active: <font color="#8AE234"><b>active (running)</b></font> since Sat 2020-03-07 19:54:27 EST; 52s ago
  Process: 15943 ExecStop=/usr/sbin/apachectl stop (code=exited, status=0/SUCCESS)
  Process: 15948 ExecStart=/usr/sbin/apachectl start (code=exited, status=0/SUCCESS)
 Main PID: 15952 (apache2)
    Tasks: 6 (limit: 4915)
   CGroup: /system.slice/apache2.service
           |-15952 /usr/sbin/apache2 -k start
           |-15953 /usr/sbin/apache2 -k start
           |-15954 /usr/sbin/apache2 -k start
           |-15955 /usr/sbin/apache2 -k start
           |-15956 /usr/sbin/apache2 -k start
           `-15957 /usr/sbin/apache2 -k start

Mar 07 19:54:27 riley-VirtualBox systemd[1]: Starting The Apache HTTP Server...
Mar 07 19:54:27 riley-VirtualBox systemd[1]: Started The Apache HTTP Server.
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<span style="background-color:#D3D7CF"><font color="#2E3436">lines 1-19/19 (END)</font></span>
























<font color="#8AE234"><b>*</b></font> apache2.service - The Apache HTTP Server
   Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: 
  Drop-In: /lib/systemd/system/apache2.service.d
           `-apache2-systemd.conf
   Active: <font color="#8AE234"><b>active (running)</b></font> since Sat 2020-03-07 19:54:27 EST; 52s ago
  Process: 15943 ExecStop=/usr/sbin/apachectl stop (code=exited, status=0/SUCCES
  Process: 15948 ExecStart=/usr/sbin/apachectl start (code=exited, status=0/SUCC
 Main PID: 15952 (apache2)
    Tasks: 6 (limit: 4915)
   CGroup: /system.slice/apache2.service
           |-15952 /usr/sbin/apache2 -k start
           |-15953 /usr/sbin/apache2 -k start
           |-15954 /usr/sbin/apache2 -k start
           |-15955 /usr/sbin/apache2 -k start
           |-15956 /usr/sbin/apache2 -k start
           `-15957 /usr/sbin/apache2 -k start

Mar 07 19:54:27 riley-VirtualBox systemd[1]: Starting The Apache HTTP Server...
Mar 07 19:54:27 riley-VirtualBox systemd[1]: Started The Apache HTTP Server.
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<font color="#73DD20"><b>~</b></font>
<span style="background-color:#D3D7CF"><font color="#2E3436">lines 1-19/19 (END)</font></span>
</pre>
