# wp-workflow
WP workflow (Český Hosting VMS)

## Prerequisites
- Apache
- PHP7
- MySQL
- Composer
- GIT
- SSH Keys + authorized_keys (Public Key) in .ssh folder on server

1. Create a DEV environment
2. Connect with SSH GIT archive on STAGING
3. GIT Pull on STAGING
4. `php composer.phar install` on STAGING
5. Create a database on STAGING
6. upload .env file and change it accordingly (database...). Do not forget change localhost to 127.0.0.1
7. Install WP
8. Activate DB Sync + DB Media
9. Sync DB from DEV to Staging
10. GIT Pull on Staging on updates

PS: Make sure "dist" folder in theme directory is not in .gitignore file and is in the repository
