# spin-wordpress
Script to create a wordpress site, using *mysql* database, *nginx* web server and *certbot* for certification.

## Requirements

The script is tested on stable debian only.
To install necessary packages:

    $ sudo apt install php php-fpm mysql nginx certbot perl wget pwgen

## Example

    $ git clone https://github.com/her01n/spin-wordpress
    $ cd spin-wordpress
    $ sudo ./spin-wordpress example.com --email=admin@example.com
