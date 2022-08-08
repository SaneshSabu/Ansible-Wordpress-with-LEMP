
# Ansible-Wordpress-with-LEMP

Sample playbook for installing Wordpress with LEMP stack on ubuntu OS.


## Packages


```bash
  - nginx
  - php-fpm
  - php-mysql
  - mariadb-server
  - python3-pymysql
```

## Usage
- Pull the repo
```python
git pull SaneshSabu/Ansible-Wordpress-with-LEMP
```
- Create the files
```python
hosts  #for ansible to deploy configuration
secret_vars #Secret variables such as username and password of the database
remote.pem # private key to access remote servers.
```
- Run the playbook
```bash
ansible-playbook -i hosts main.yml
```


#

