# Simple TOR Socks Proxy Container

Dockerfile to setup and compile tor software usgin Debian. When ran tor starts with a SOCKS5 server accessible on port 9150
(This does not set up a tor relay or exit node).

### Running

*Verbose:*
```bash
$ docker run --name tor -ti -p 9050:9050 xxx/tor
```

*As a Dameon:*
```bash
$ docker run --name tor -d -p 9050:9050 xxx/tor
```
