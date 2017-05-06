# wp-workflow
WP workflow (Český Hosting VMS)

1. Create a DEV environment
2. Connect with SSH GIT archive on STAGING
3. GIT Pull on STAGING
4. `php composer.phar install` on STAGING
5. Create a database on STAGING
6. upload .env file and change it accordingly (database...). Do not forget change localhost to 127.0.0.1
7. Install WP
8. Activate DB Sync + DB Media
9. Sync DB from DEV to Staging
