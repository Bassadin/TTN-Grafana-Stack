# TTN-Grafana-Stack

## What is this?

I needed a dockerized version of a Grafana/Influx/Telegraf stack that gets data from _The Things Network_ and displays them in a Grafana dashboard. Feel free to modify :)

## Configuration

1. Copy the `config/configuration.env.example` file to `config/configuration.env` and edit the file to match your configuration.
2. Copy `the ttn/ttn_config.env.example` file to `ttn/ttn_config.env` and edit the file to match your configuration.
3. Perform a `docker-compose up -d` to start the stack.
