# --DESCRIPTION--

![https://cloud.docker.com/u/pionl/repository/docker/--IMAGE_NAME--](https://img.shields.io/docker/stars/--IMAGE_NAME--?style=flat-square)
![https://cloud.docker.com/u/pionl/repository/docker/--IMAGE_NAME--](https://img.shields.io/docker/pulls/--IMAGE_NAME--?style=flat-square)
![https://github.com/--IMAGE_NAME--](https://img.shields.io/github/license/--IMAGE_NAME--?style=flat-square)

A docker image for your Laravel application with PHP with Glue installed. Image uses 
[pionl/docker-php-laravel-ci image](https://github.com/pionl/docker-php-laravel-ci).

## Glue

Glue is a simple command line tool to generate sprites using any kind of source images like PNG, JPEG or GIF. Glue will generate a unique PNG file containing every source image and a map file including the necessary information to use it.

[Glue documentation](https://glue.readthedocs.io/en/latest/)

## Usage
```
docker run --IMAGE_NAME--:7.2 glue --version
```

### Gitlab CI usage

Gitlab CI usage

```shell
image: --IMAGE_NAME--:7.2
```

### Tags

--TAGS--

## Built With

> This package is powered by docker work flow cli tool [wf-docker](https://github.com/wrk-flow/wf-docker).

* PHP related SW from [pionl/docker-php-laravel-ci image](https://github.com/pionl/docker-php-laravel-ci)
* [Glue](https://glue.readthedocs.io/en/latest/)

## Find Us

* [GitHub](https://github.com/--IMAGE_NAME--)
* [Docker Hub](https://cloud.docker.com/repository/docker/--IMAGE_NAME--)

## Contributions

1. Run `npm install`
2. Change the `Dockerfile.template`
3. For new php versions edit `package.json` and `wf-docker.tags` property
4. Use `npm run build` to build image

> See package.json scripts for advanced usage or [wf-docker](https://github.com/wrk-flow/wf-docker)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
