# Docker Bitpoll

Docker image for [Bitpoll](https://github.com/fsinfuhh/Bitpoll), prepared for use with a postgres database and behind a reverse proxy.

Adjust the settings within the `docker-compose.yml` and `settings_local.py` file before the first run.
Within the docker-compose-file a volume for the database is predefined, you can also delete the mountpoint if you want.

Supplemented with DjangoWhiteNoise for usage without debug mode but with proxy.
