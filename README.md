# docker-collectd

Basic collectd image, can be used as client or server, depend on your configuration.

Docker Hub: https://hub.docker.com/r/maxwayt/karhu/

## Running

Minimal command:

```
docker run -d -v /your/configurations:/etc/collectd/collectd.conf.d maxwayt/collectd
```

No environment variable, everything should be mount :)

## License

MIT
