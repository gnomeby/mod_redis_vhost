mod_redis_vhost
===============

The lighttpd server module that let define vhost configuration using redis.
At the moment it replaces a part of mod_fastcgi realization.

Typical request from lighht site:
HMGET site:example.org host port docroot

#### Requirements:
* Hiredis (https://github.com/redis/hiredis)

#### TODO
* Support www. as alias
* Support TTL
* Rename into mod_redis_vhost
