Example PHP.ini config files for CLI and FPM. Designed with sane upload limits, security and speed in mind.


Things you may wish to change
-----------------------------

memory_limit = 512M
post_max_size = 512M
upload_max_filesize = 500M
date.timezone = 'Europe/London'



Things to be aware of
---------------------

For PHP-FPM `allow_url_fopen = Off`. This is considered good practice. However some badly coded applications may complain, (WordPress plugins are a prime culprit). I would recommend fixing the plugin rather than enabling it.
