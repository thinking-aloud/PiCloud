OwncloudPie
===========

Shell script for installing and updating Owncloud on the Raspberry Pi. The script either performs a new installation of the newest Owncloud release or, if already installed, performs an upgrade to the newest release. When doing a new installation the script installs the Apache 2 webserver together with some needed Apache modules and the SQLite database package. Afterwards it downloads and installs Owncloud 4.0.5, which is the newest release at this time. 

This script was tested on the Raspbian distribution from 2013-01-23 with owncloud 4.5.6.


First of all, make sure that Git is installed:

```shell
sudo apt-get update
sudo apt-get install -y git dialog
```

Then you can download the latest OwncloudPie setup script with

```shell
cd
git clone git://github.com/petrockblog/OwncloudPie.git
```

The script is executed with 

```shell
cd OwncloudPie
chmod +x owncloudpie_setup.sh
sudo ./owncloudpie_setup.sh
```

For more information visit the blog at http://petrockblog.wordpress.com or the repository at https://github.com/petrockblog/OwncloudPie.

Have fun!
