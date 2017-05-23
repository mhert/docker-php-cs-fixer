# docker-php-cs-fixer

A docker image to run php-cs-fixer(https://github.com/FriendsOfPHP/PHP-CS-Fixer)

## Usage 

    docker run -u ${UID}:${GID} -v ${PWD}:/src mhert/php-cs-fixer --verbose fix /src
