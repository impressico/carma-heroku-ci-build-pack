# Heroku CodeIgnitor Buildpack for CI
# Heroku buildpack: CodeIgniter on Heroku

### This is a Heroku buildpack for running [CodeIgniter](http://http://ellislab.com/codeigniter) on [Heroku](http://heroku.com)

It uses this [CodeIgniter](http://github.com/joshlarsen/codeigniter-on-heroku) project template to bootstrap a tuned CodeIgniter site built on the following stack:

* `nginx-1.3.11` - Nginx for serving web content.  Built specifically for Heroku.  [See compile options](https://github.com/mchung/heroku-buildpack-wordpress/blob/master/support/package_nginx).
* `php-5.4.11` - PHP-FPM for process management and APC for caching opcodes.  [See compile options](https://github.com/mchung/heroku-buildpack-wordpress/blob/master/support/package_php).
* `wordpress-3.5.1` - Downloaded directly [from wordpress.org](http://wordpress.org/download/release-archive/).
* `MySQL` - ClearDB for the MySQL backend.
* `Sendgrid` - Sendgrid for the email backend.
* `MemCachier` - MemCachier for the memcached backend.
