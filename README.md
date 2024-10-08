# WP Secure Deploy

Security configs and deployment tips for a secure WordPress setup.

## Links

- [WordPress Security](https://developer.wordpress.org/advanced-administration/security/hardening/)
- [Two Factor Authentication plugin](https://de.wordpress.org/plugins/wp-2fa/)

## Usage

All codes should be inserted right at the beginning of the files.

- Add code from [.htaccess](.htaccess) to your `.htaccess` file.  
- Add code from [.htaccess](.htaccess) to your `wp-content/themes/.htaccess` file (if it doesn't exist, create it).
- Add code from [wp-config.php](wp-config.php) to your `wp-config.php` file.
- Add code from [robots.txt](robots.txt) to your `robots.txt` file.

## Recommendations

- Enable Two Factor Authentication
- Update WordPress and plugins/themes
- Verify backups are working
- Verify Site Health /wp-admin/site-health.php
- Setup WordPress Cron Jobs (One for Each Site in a Multisite)

## Advanced

- Use a creative admin user name
