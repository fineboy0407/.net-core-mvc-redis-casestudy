# Redis with ASP.net MVC Core Web Application

This is an example application illustrating different methods to integrate Redis into ASP.net MVC core web application.

## Redis Installation

There are anumber of ways to install Redis depending on your operating system or development environment. 

### Windows

The Microsoft Open Tech group develops and maintains Windows port targeting Win64 available. 
Download the stable release
[MicrosoftArchive/Redis](https://github.com/MicrosoftArchive/redis/releases)

### Linux (Ubuntu/Debian)

On a Ubuntu Desktop Redis can be installed via the apt repository
```bash
sudo apt install redis-server
sudo apt install redis-tools
```

### MacOSX 

```
    brew install redis
 
    #Launch redis on restart
    ln -sfv /usr/local/opt/redis/*.plist ~/Library/LaunchAgents`

```


### Docker

Check out the official [Redis repository on the Docker Store](https://store.docker.com/images/redis)

```bash
docker pull redis 
docker run --name some-redis -d redis
```
