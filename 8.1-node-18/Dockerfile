FROM --platform=linux/amd64 pionl/docker-php-laravel-ci:8.1-node-18

MAINTAINER Martin Kluska <martin@kluska.cz>

########################################################################################################################
##### Python with glue depedencies
########################################################################################################################

RUN apt-get update && apt-get install -yq \
    glue-sprite \
    && rm -r /var/lib/apt/lists/*

# Create alias for glue (python package name)

RUN ln -s /usr/bin/glue-sprite /usr/bin/glue
