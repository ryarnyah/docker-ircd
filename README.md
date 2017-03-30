# Docker IRCd container

## To build it
```bash
docker build -t ryarnyah/docker-ircd:latest .
```

## To run it
```bash
docker run -d -p 6667:6667 --drop-cap=ALL ryarnyah/docker-ircd:latest
```
