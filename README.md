# docker-ngxpasswd
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fliuchong%2Fdocker-nginx-htpasswd.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fliuchong%2Fdocker-nginx-htpasswd?ref=badge_shield)

Docker of nginx proxy tool with username/password.

## Usage:

``` bash
docker run --rm -it liuchong/nginx-htpasswd start -h
usage:
 -u [username] your http username
 -p [password] your http password
 -c [script] your specified script
 -a [args] args of your script
 -P [args] nginx listening port
 -X [args] proxy_pass of host:port
```

Please check [examples](https://github.com/liuchong/docker-nginx-htpasswd/tree/master/examples):

[proxy-only](https://github.com/liuchong/docker-nginx-htpasswd/tree/master/examples/proxy-only)

[redis-stat](https://github.com/liuchong/docker-nginx-htpasswd/tree/master/examples/redis-stat)

Certainly, you can copy and paste the codes from this repository to fit your need, enjoy your self!

## License

[MIT](LICENSE)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fliuchong%2Fdocker-nginx-htpasswd.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fliuchong%2Fdocker-nginx-htpasswd?ref=badge_large)