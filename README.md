# WP Secure Deploy

Security configs and deployment tips for a secure WordPress setup.

## Links

- [WordPress Security](https://developer.wordpress.org/advanced-administration/security/hardening/)
- [Two Factor Authentication plugin](https://de.wordpress.org/plugins/wp-2fa/)

## Usage

- Add code from [.htaccess](.htaccess) to your `.htaccess` file.  
**Note:** to ensure the code is not overwritten by WordPress, place it outside the # BEGIN WordPress and # END WordPress tags.
- Add code from [wp-config.php](wp-config.php) to your `wp-config.php` file.
- Add code from [robots.txt](robots.txt) to your `robots.txt` file.
- Enable Two Factor Authentication

## Recommendations

- Use a creative admin user name
- You should always keep up to date with the latest version of WordPress and plugins/themes
- Verify backups are working
- Verify Site Health /wp-admin/site-health.php
