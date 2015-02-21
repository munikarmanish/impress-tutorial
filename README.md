# impress-tutorial
## How to get started

Clone this repo
'''
	git clone 
'''

Database migration
'''
	mysql -u $USER -p < db_migration.sh
'''

Edit default configuration
'''
	emacs connect.php
'''

## Major source of error
### Permission
set permisssion of tutorial to be writable by others
'''
	chmod o+w tutorial
'''
