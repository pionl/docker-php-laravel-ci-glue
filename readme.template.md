# --DESCRIPTION--

A docker image `linux/amd64` for your Laravel application with PHP with Glue installed. Image uses 
[pionl/docker-php-laravel-ci image](https://github.com/pionl/docker-php-laravel-ci).

## Glue

Glue is a simple command line tool to generate sprites using any kind of source images like PNG, JPEG or GIF. Glue will generate a unique PNG file containing every source image and a map file including the necessary information to use it.

[Glue documentation](https://glue.readthedocs.io/en/latest/)

## Usage
```
docker run --IMAGE_NAME--:8.2-node-18 --version
```

### Gitlab CI usage

Gitlab CI usage

```shell
image: --IMAGE_NAME--:8.2-node-18
```

### Tags

![https://github.com/--IMAGE_NAME--](https://img.shields.io/github/license/--IMAGE_NAME--?style=flat-square)
--TAGS--

### Deprecated tags

| Image                                                       | Badges                                                                                                                  |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| **pionl/docker-php-laravel-ci-glue:7.4-node-17**            | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.4-node-17?style=flat-square)            |
| **pionl/docker-php-laravel-ci-glue:7.4-node-14**            | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.4-node-14?style=flat-square)            |
| **pionl/docker-php-laravel-ci-glue:7.4-node-10**            | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.4-node-10?style=flat-square)            |
| **pionl/docker-php-laravel-ci-glue:7.2-node-17**            | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.2-node-17?style=flat-square)            |
| **pionl/docker-php-laravel-ci-glue:7.2-node-17-composer-1** | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.2-node-17-composer-1?style=flat-square) |
| **pionl/docker-php-laravel-ci-glue:7.2-node-14**            | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.2-node-14?style=flat-square)            |
| **pionl/docker-php-laravel-ci-glue:7.2-node-14-composer-1** | ![](https://img.shields.io/docker/image-size/pionl/docker-php-laravel-ci-glue/7.2-node-14-composer-1?style=flat-square) |

## Built With

> This package is powered by docker work flow cli tool [wf-docker](https://github.com/wrk-flow/wf-docker).

* PHP related SW from [pionl/docker-php-laravel-ci image](https://github.com/pionl/docker-php-laravel-ci)
* [Glue](https://glue.readthedocs.io/en/latest/)

## Find Us

* [GitHub](https://github.com/--IMAGE_NAME--)
* [Docker Hub](https://cloud.docker.com/repository/docker/--IMAGE_NAME--)

## Contributions

1. Run `npm install` or install [wf-docker](https://github.com/wrk-flow/wf-docker) globally.
2. Change the `Dockerfile.template`
3. For new php versions edit `package.json` and `wf-docker.tags` property
4. Use `npm run build` to build image

> See package.json scripts for advanced usage or [wf-docker](https://github.com/wrk-flow/wf-docker)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
