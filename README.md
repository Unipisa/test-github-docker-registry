# Test of GitHub Docker registry by GitHub Actions

https://github.blog/2020-09-01-introducing-github-container-registry/

enabled on org

https://docs.github.com/en/packages/guides/enabling-improved-container-support#enabling-github-container-registry-for-your-organization-account

## How to run ?

The project launch is in two parts: build and start.

### Build

```
$ docker build -t [image_name] . 
```

### Launch

```
$ docker run [image_name]
```

## Author

- **Gaël THOMAS** - [gael-thomas](https://github.com/gael-thomas)
