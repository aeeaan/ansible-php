correcthorse.php
=========

A role for installing php.

Role Variables
--------------

| Variable                              | Default				| Notes					|
| :---                                  | :---                          	| :---					|
| php_base_name				| php					| php, php55u, php56u, etc		|
| php_version				| 5.4					|					|
| php_fpm				| true					|					|
| php_use_memcache			| true					|					|
| php_use_memcached			| false					|					|
| php_timezone				| America/New_York			|					|
| php_upload_max			| 30M					|					|
| php_post_max				| 30M					|					|
| php_html_errors			| "Off"					|					|
| php_memory_limit			| 256M					|					|
| php_expose_php			| "Off"					|					|
| php_max_execution_time		| 120					|					|
| php_error_reporting			| "E_ALL & ~E_DEPRECATED & ~E_STRICT"	|					|
| php_display_errors			| "Off"	   		   		|					|
| php_display_startup_errors		| "Off"					|					|
| php_realpath_cache_size		| 16k					|					|
| php_realpath_cache_ttl		| 120					|					|

Dependencies
------------

TODO

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.php }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
