# Simple Catalog
Simple catalog demo using Flask and SQLAlchemy

## Requirements
- Python 2.7
- [Flask](http://flask.pocoo.org/)
- [Flask-SeaSurf](https://flask-seasurf.readthedocs.org/en/latest/)
- [SQLAlchemy](http://www.sqlalchemy.org/)
- [Oauth2client](https://github.com/google/oauth2client)
- [Vagrant](https://www.vagrantup.com/)

## To Run
Start VM  
```
cd vagrant/
vagrant up
```
SSH VM
```
vagrant ssh
```
Set up Database
```
cd /vagrant/catalog/
python database_init.py
```
Run Server
```
cd /vagrant/catalog/
python app.py
```
Access the demo
```
http://localhost:5000/
```
Exit SSH session
```
exit
```
Suspend VM
```
vagrant suspend
```

## Useful Links
How do I destroy a VM when I deleted the .vagrant file?
http://stackoverflow.com/questions/15408969/how-do-i-destroy-a-vm-when-i-deleted-the-vagrant-file  

## Author
**[Jack Chang]**

[Jack Chang]: https://wei0831.net
