# Heroku CodeIgnitor Buildpack for CI

* `nginx-1.3.11` - Nginx for serving web content.  Built specifically for Heroku.  [See compile options](https://github.com/mchung/heroku-buildpack-wordpress/blob/master/support/package_nginx).
* `php-5.4.11` - PHP-FPM for process management and APC for caching opcodes.  [See compile options](https://github.com/mchung/heroku-buildpack-wordpress/blob/master/support/package_php).
* `MySQL` - ClearDB for the MySQL backend.
