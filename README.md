
# PHP image for Bitbucket Pipelines

Customized PHP image with all the required extensions.

## Status

![CI](https://github.com/housfy/php-7.3-bitbucket-pipelines/workflows/CI/badge.svg)

## Test and build

```
docker build -t housfy-php-7.3 .
```
When you commit to the repo it will then trigger the image to be rebuilt on DockerHub.

Run the container locally after building.

```
docker run -it --name housfy-php-7.3 --rm  housfy-php-7.3:latest
```