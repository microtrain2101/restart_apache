# restart_apache
A simple Bash script for reloading Apache VHost configs

## Usage
Clone the repository or download the latest release. 

From a command-line call re.sh with two arguments.
1. The vhost configuration
1. The service directive {restart|reload}
```sh
cd ~
cd restart_apache
sudo ./re.sh 000* restart
[enter password]
sudo systemctl reload apache2
```
