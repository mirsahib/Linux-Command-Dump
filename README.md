| Description                           |                  command                  |
| ------------------------------------- | :---------------------------------------: |
| show all installed packages           |           apt list --installed            |
| show all installed packages           |           apt list --installed            |
| show all installed package with info  |         apt list -- installed -v          |
| show selected package location        | dpkg -L <package name> eg: dpkg -L tomcat |
| remove apt package                    |    sudo apt-get remove <package name>     |
| remove apt package with config file   | sudo apt-get remove --purge <package name |
| remove old cache and outdated package |            sudo apt-get clean             |
