# squid3-docker

Squid proxy on Alpine Linux. Configure via mount @ /var/squid/squid.conf

E.g.

```
docker run --rm -p 3128:3128 -v $PWD:/var/squid mkscrg/squid3
```
