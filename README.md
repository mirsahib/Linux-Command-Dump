| Description                           |                  command                  |
| ------------------------------------- | :---------------------------------------: |
| show all installed packages           |           apt list --installed            |
| show all installed packages           |           apt list --installed            |
| show all installed package with info  |         apt list -- installed -v          |
| show selected package location        | dpkg -L <package name> eg: dpkg -L tomcat |
| remove apt package                    |    sudo apt-get remove <package name>     |
| remove apt package with config file   | sudo apt-get remove --purge <package name |
| remove old cache and outdated package |            sudo apt-get clean             |
| move file to protected section        | sudo mv <filename> <location> eg: sudo mv test.txt /usr/share |
| install tree | sudo apt install tree |
| show directory tree | tree |
| show directory tree with level  | tree -L <level value 1+ > eg: tree -L 1 |
| save directory tree with level | tree -L <level value 1+> --charset unicode > fileName.txt eg: tree -L 2 --charset unicode /home/<username>/Desktop/filename.txt |
