ntopng-docker
=============

[ ![Codeship Status for wincus/ntopng-docker](https://app.codeship.com/projects/70f9be00-b34c-0134-bf10-2a924262b5e8/status?branch=master)](https://app.codeship.com/projects/193452)

## ntopng Dock Builder

#### Install & Run
```
$ export NTOP_ADMIN_PASSWORD=<md5 admin password>
$ docker run --net=host -t -p 3000:3000 -e NTOP_ADMIN_PASSWORD=$NTOP_ADMIN_PASSWORD  wincus/ntop:dev <ntopng arguments>
```
