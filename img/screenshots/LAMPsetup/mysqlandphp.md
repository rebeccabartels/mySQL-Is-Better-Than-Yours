<pre><font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ nano info.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo nano info.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  info.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  info.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ rm info.php 
rm: remove write-protected regular file &apos;info.php&apos;? n
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  info.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo rm info.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ allow_url_fopen on
allow_url_fopen: command not found
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo apt-get update
[sudo] password for riley: 
Hit:1 http://us.archive.ubuntu.com/ubuntu bionic InRelease
Get:2 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease [74.6 kB] 
Get:4 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]    
Get:5 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 DEP-11 Metadata [307 kB]
Get:6 http://us.archive.ubuntu.com/ubuntu bionic-updates/main DEP-11 48x48 Icons [73.8 kB]
Get:7 http://us.archive.ubuntu.com/ubuntu bionic-updates/main DEP-11 64x64 Icons [140 kB]
Get:8 http://us.archive.ubuntu.com/ubuntu bionic-updates/universe amd64 DEP-11 Metadata [264 kB]
Get:9 http://us.archive.ubuntu.com/ubuntu bionic-updates/universe DEP-11 48x48 Icons [196 kB]
Get:10 http://us.archive.ubuntu.com/ubuntu bionic-updates/universe DEP-11 64x64 Icons [448 kB]
Get:11 http://us.archive.ubuntu.com/ubuntu bionic-updates/multiverse amd64 DEP-11 Metadata [2,468 B]
Get:12 http://us.archive.ubuntu.com/ubuntu bionic-backports/universe amd64 DEP-11 Metadata [7,984 B]
Get:13 http://security.ubuntu.com/ubuntu bionic-security/main amd64 DEP-11 Metadata [38.5 kB]
Get:14 http://security.ubuntu.com/ubuntu bionic-security/main DEP-11 48x48 Icons [17.6 kB]
Get:15 http://security.ubuntu.com/ubuntu bionic-security/main DEP-11 64x64 Icons [41.5 kB]
Get:16 http://security.ubuntu.com/ubuntu bionic-security/universe amd64 DEP-11 Metadata [42.1 kB]
Get:17 http://security.ubuntu.com/ubuntu bionic-security/universe DEP-11 64x64 Icons [106 kB]
Get:18 http://security.ubuntu.com/ubuntu bionic-security/multiverse amd64 DEP-11 Metadata [2,464 B]
Fetched 1,939 kB in 3s (747 kB/s)                                              
Reading package lists... Done
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ip addr
1: lo: &lt;LOOPBACK,UP,LOWER_UP&gt; mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: enp0s3: &lt;BROADCAST,MULTICAST,UP,LOWER_UP&gt; mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:61:c4:c8 brd ff:ff:ff:ff:ff:ff
    inet 10.0.2.15/24 brd 10.0.2.255 scope global dynamic noprefixroute enp0s3
       valid_lft 80707sec preferred_lft 80707sec
    inet6 fe80::a9de:59b5:6607:8cb1/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ apache2
[Sat Mar 07 19:51:43.621131 2020] [core:warn] [pid 15921] AH00111: Config variable ${APACHE_RUN_DIR} is not defined
apache2: Syntax error on line 80 of /etc/apache2/apache2.conf: DefaultRuntimeDir must be a valid directory, absolute or relative to ServerRoot
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ cat index.html 

&lt;!DOCTYPE html PUBLIC &quot;-//W3C//DTD XHTML 1.0 Transitional//EN&quot; &quot;http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd&quot;&gt;
&lt;html xmlns=&quot;http://www.w3.org/1999/xhtml&quot;&gt;
  &lt;!--
    Modified from the Debian original for Ubuntu
    Last updated: 2016-11-16
    See: https://launchpad.net/bugs/1288690
  --&gt;
  &lt;head&gt;
    &lt;meta http-equiv=&quot;Content-Type&quot; content=&quot;text/html; charset=UTF-8&quot; /&gt;
    &lt;title&gt;Apache2 Ubuntu Default Page: It works&lt;/title&gt;
    &lt;style type=&quot;text/css&quot; media=&quot;screen&quot;&gt;
  * {
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }

  body, html {
    padding: 3px 3px 3px 3px;

    background-color: #D8DBE2;

    font-family: Verdana, sans-serif;
    font-size: 11pt;
    text-align: center;
  }

  div.main_page {
    position: relative;
    display: table;

    width: 800px;

    margin-bottom: 3px;
    margin-left: auto;
    margin-right: auto;
    padding: 0px 0px 0px 0px;

    border-width: 2px;
    border-color: #212738;
    border-style: solid;

    background-color: #FFFFFF;

    text-align: center;
  }

  div.page_header {
    height: 99px;
    width: 100%;

    background-color: #F5F6F7;
  }

  div.page_header span {
    margin: 15px 0px 0px 50px;

    font-size: 180%;
    font-weight: bold;
  }

  div.page_header img {
    margin: 3px 0px 0px 40px;

    border: 0px 0px 0px;
  }

  div.table_of_contents {
    clear: left;

    min-width: 200px;

    margin: 3px 3px 3px 3px;

    background-color: #FFFFFF;

    text-align: left;
  }

  div.table_of_contents_item {
    clear: left;

    width: 100%;

    margin: 4px 0px 0px 0px;

    background-color: #FFFFFF;

    color: #000000;
    text-align: left;
  }

  div.table_of_contents_item a {
    margin: 6px 0px 0px 6px;
  }

  div.content_section {
    margin: 3px 3px 3px 3px;

    background-color: #FFFFFF;

    text-align: left;
  }

  div.content_section_text {
    padding: 4px 8px 4px 8px;

    color: #000000;
    font-size: 100%;
  }

  div.content_section_text pre {
    margin: 8px 0px 8px 0px;
    padding: 8px 8px 8px 8px;

    border-width: 1px;
    border-style: dotted;
    border-color: #000000;

    background-color: #F5F6F7;

    font-style: italic;
  }

  div.content_section_text p {
    margin-bottom: 6px;
  }

  div.content_section_text ul, div.content_section_text li {
    padding: 4px 8px 4px 16px;
  }

  div.section_header {
    padding: 3px 6px 3px 6px;

    background-color: #8E9CB2;

    color: #FFFFFF;
    font-weight: bold;
    font-size: 112%;
    text-align: center;
  }

  div.section_header_red {
    background-color: #CD214F;
  }

  div.section_header_grey {
    background-color: #9F9386;
  }

  .floating_element {
    position: relative;
    float: left;
  }

  div.table_of_contents_item a,
  div.content_section_text a {
    text-decoration: none;
    font-weight: bold;
  }

  div.table_of_contents_item a:link,
  div.table_of_contents_item a:visited,
  div.table_of_contents_item a:active {
    color: #000000;
  }

  div.table_of_contents_item a:hover {
    background-color: #000000;

    color: #FFFFFF;
  }

  div.content_section_text a:link,
  div.content_section_text a:visited,
   div.content_section_text a:active {
    background-color: #DCDFE6;

    color: #000000;
  }

  div.content_section_text a:hover {
    background-color: #000000;

    color: #DCDFE6;
  }

  div.validator {
  }
    &lt;/style&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;div class=&quot;main_page&quot;&gt;
      &lt;div class=&quot;page_header floating_element&quot;&gt;
        &lt;img src=&quot;/icons/ubuntu-logo.png&quot; alt=&quot;Ubuntu Logo&quot; class=&quot;floating_element&quot;/&gt;
        &lt;span class=&quot;floating_element&quot;&gt;
          Apache2 Ubuntu Default Page
        &lt;/span&gt;
      &lt;/div&gt;
&lt;!--      &lt;div class=&quot;table_of_contents floating_element&quot;&gt;
        &lt;div class=&quot;section_header section_header_grey&quot;&gt;
          TABLE OF CONTENTS
        &lt;/div&gt;
        &lt;div class=&quot;table_of_contents_item floating_element&quot;&gt;
          &lt;a href=&quot;#about&quot;&gt;About&lt;/a&gt;
        &lt;/div&gt;
        &lt;div class=&quot;table_of_contents_item floating_element&quot;&gt;
          &lt;a href=&quot;#changes&quot;&gt;Changes&lt;/a&gt;
        &lt;/div&gt;
        &lt;div class=&quot;table_of_contents_item floating_element&quot;&gt;
          &lt;a href=&quot;#scope&quot;&gt;Scope&lt;/a&gt;
        &lt;/div&gt;
        &lt;div class=&quot;table_of_contents_item floating_element&quot;&gt;
          &lt;a href=&quot;#files&quot;&gt;Config files&lt;/a&gt;
        &lt;/div&gt;
      &lt;/div&gt;
--&gt;
      &lt;div class=&quot;content_section floating_element&quot;&gt;


        &lt;div class=&quot;section_header section_header_red&quot;&gt;
          &lt;div id=&quot;about&quot;&gt;&lt;/div&gt;
          It works!
        &lt;/div&gt;
        &lt;div class=&quot;content_section_text&quot;&gt;
          &lt;p&gt;
                This is the default welcome page used to test the correct 
                operation of the Apache2 server after installation on Ubuntu systems.
                It is based on the equivalent page on Debian, from which the Ubuntu Apache
                packaging is derived.
                If you can read this page, it means that the Apache HTTP server installed at
                this site is working properly. You should &lt;b&gt;replace this file&lt;/b&gt; (located at
                &lt;tt&gt;/var/www/html/index.html&lt;/tt&gt;) before continuing to operate your HTTP server.
          &lt;/p&gt;


          &lt;p&gt;
                If you are a normal user of this web site and don&apos;t know what this page is
                about, this probably means that the site is currently unavailable due to
                maintenance.
                If the problem persists, please contact the site&apos;s administrator.
          &lt;/p&gt;

        &lt;/div&gt;
        &lt;div class=&quot;section_header&quot;&gt;
          &lt;div id=&quot;changes&quot;&gt;&lt;/div&gt;
                Configuration Overview
        &lt;/div&gt;
        &lt;div class=&quot;content_section_text&quot;&gt;
          &lt;p&gt;
                Ubuntu&apos;s Apache2 default configuration is different from the
                upstream default configuration, and split into several files optimized for
                interaction with Ubuntu tools. The configuration system is
                &lt;b&gt;fully documented in
                /usr/share/doc/apache2/README.Debian.gz&lt;/b&gt;. Refer to this for the full
                documentation. Documentation for the web server itself can be
                found by accessing the &lt;a href=&quot;/manual&quot;&gt;manual&lt;/a&gt; if the &lt;tt&gt;apache2-doc&lt;/tt&gt;
                package was installed on this server.

          &lt;/p&gt;
          &lt;p&gt;
                The configuration layout for an Apache2 web server installation on Ubuntu systems is as follows:
          &lt;/p&gt;
          &lt;pre&gt;
/etc/apache2/
|-- apache2.conf
|       `--  ports.conf
|-- mods-enabled
|       |-- *.load
|       `-- *.conf
|-- conf-enabled
|       `-- *.conf
|-- sites-enabled
|       `-- *.conf
          &lt;/pre&gt;
          &lt;ul&gt;
                        &lt;li&gt;
                           &lt;tt&gt;apache2.conf&lt;/tt&gt; is the main configuration
                           file. It puts the pieces together by including all remaining configuration
                           files when starting up the web server.
                        &lt;/li&gt;

                        &lt;li&gt;
                           &lt;tt&gt;ports.conf&lt;/tt&gt; is always included from the
                           main configuration file. It is used to determine the listening ports for
                           incoming connections, and this file can be customized anytime.
                        &lt;/li&gt;

                        &lt;li&gt;
                           Configuration files in the &lt;tt&gt;mods-enabled/&lt;/tt&gt;,
                           &lt;tt&gt;conf-enabled/&lt;/tt&gt; and &lt;tt&gt;sites-enabled/&lt;/tt&gt; directories contain
                           particular configuration snippets which manage modules, global configuration
                           fragments, or virtual host configurations, respectively.
                        &lt;/li&gt;

                        &lt;li&gt;
                           They are activated by symlinking available
                           configuration files from their respective
                           *-available/ counterparts. These should be managed
                           by using our helpers
                           &lt;tt&gt;
                                a2enmod,
                                a2dismod,
                           &lt;/tt&gt;
                           &lt;tt&gt;
                                a2ensite,
                                a2dissite,
                            &lt;/tt&gt;
                                and
                           &lt;tt&gt;
                                a2enconf,
                                a2disconf
                           &lt;/tt&gt;. See their respective man pages for detailed information.
                        &lt;/li&gt;

                        &lt;li&gt;
                           The binary is called apache2. Due to the use of
                           environment variables, in the default configuration, apache2 needs to be
                           started/stopped with &lt;tt&gt;/etc/init.d/apache2&lt;/tt&gt; or &lt;tt&gt;apache2ctl&lt;/tt&gt;.
                           &lt;b&gt;Calling &lt;tt&gt;/usr/bin/apache2&lt;/tt&gt; directly will not work&lt;/b&gt; with the
                           default configuration.
                        &lt;/li&gt;
          &lt;/ul&gt;
        &lt;/div&gt;

        &lt;div class=&quot;section_header&quot;&gt;
            &lt;div id=&quot;docroot&quot;&gt;&lt;/div&gt;
                Document Roots
        &lt;/div&gt;

        &lt;div class=&quot;content_section_text&quot;&gt;
            &lt;p&gt;
                By default, Ubuntu does not allow access through the web browser to
                &lt;em&gt;any&lt;/em&gt; file apart of those located in &lt;tt&gt;/var/www&lt;/tt&gt;,
                &lt;a href=&quot;http://httpd.apache.org/docs/2.4/mod/mod_userdir.html&quot; rel=&quot;nofollow&quot;&gt;public_html&lt;/a&gt;
                directories (when enabled) and &lt;tt&gt;/usr/share&lt;/tt&gt; (for web
                applications). If your site is using a web document root
                located elsewhere (such as in &lt;tt&gt;/srv&lt;/tt&gt;) you may need to whitelist your
                document root directory in &lt;tt&gt;/etc/apache2/apache2.conf&lt;/tt&gt;.
            &lt;/p&gt;
            &lt;p&gt;
                The default Ubuntu document root is &lt;tt&gt;/var/www/html&lt;/tt&gt;. You
                can make your own virtual hosts under /var/www. This is different
                to previous releases which provides better security out of the box.
            &lt;/p&gt;
        &lt;/div&gt;

        &lt;div class=&quot;section_header&quot;&gt;
          &lt;div id=&quot;bugs&quot;&gt;&lt;/div&gt;
                Reporting Problems
        &lt;/div&gt;
        &lt;div class=&quot;content_section_text&quot;&gt;
          &lt;p&gt;
                Please use the &lt;tt&gt;ubuntu-bug&lt;/tt&gt; tool to report bugs in the
                Apache2 package with Ubuntu. However, check &lt;a
                href=&quot;https://bugs.launchpad.net/ubuntu/+source/apache2&quot;
                rel=&quot;nofollow&quot;&gt;existing bug reports&lt;/a&gt; before reporting a new bug.
          &lt;/p&gt;
          &lt;p&gt;
                Please report bugs specific to modules (such as PHP and others)
                to respective packages, not to the web server itself.
          &lt;/p&gt;
        &lt;/div&gt;




      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;validator&quot;&gt;
    &lt;/div&gt;
  &lt;/body&gt;
&lt;/html&gt;

<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ touch index.php
touch: cannot touch &apos;index.php&apos;: Permission denied
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo touch index.php
[sudo] password for riley: 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  index.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ echo test &gt; index.php 
bash: index.php: Permission denied
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo echo test &gt; index.php
bash: index.php: Permission denied
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  index.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ cat index.php 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  index.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo nano index.php 
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  index.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ cat index.
cat: index.: No such file or directory
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ cat index.php 
test
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ sudo apt-get update
[sudo] password for riley: 
Hit:1 http://us.archive.ubuntu.com/ubuntu bionic InRelease
Get:2 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease [74.6 kB] 
Get:4 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]    
Fetched 252 kB in 1s (168 kB/s)                              
Reading package lists... Done
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
index.html  index.php
<font color="#8AE234"><b>riley@riley-VirtualBox</b></font>:<font color="#729FCF"><b>/var/www/html</b></font>$ ls
</pre>
