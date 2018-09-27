# Forecast-manifest

This repository contain configuration file to run:

- [gMarcone](https://github.com/rodrwan/gmarcone)
- [mAdams](https://github.com/rodrwan/madams)
- [Traefik](https://traefik.io/)
- [Redis](https://redis.io/)

in a docker environment

### Development

to run the whole system on your machine you need to had installed **docker** with **docker-compose**:

by running:

```sh
$ docker-compose up
```

you'll mount the whole forecast system.

### Production

The system is running on docker-swarm in heroku:

[Frontend APP](http://dockhero-rugged-50468.dockhero.io/)
[Traefik Dashboard](http://dockhero-rugged-50468.dockhero.io:8080/)

