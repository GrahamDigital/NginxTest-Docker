# Grahamdigital/NginxTest

The purpose of this docker containers is simple, it just runs a quick test on your nginx config files. This is useful for a quick test in Jenkins without having to install any other packages.

## Usage

`docker run -v YOUR_CONFIG_PATH/:/etc/nginx/sites-enabled/:ro Grahamdigital/NginxTest