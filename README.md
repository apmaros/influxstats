# Influx Stats 
Dockerized metrics platform using StatsD, Grafana, InfuxDB and Telegraf

[telegraf](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/influxdb) plugin is used to collect metrics which are stored in InfluxDB.

See [telegraf.conf](etc/telegraf.conf) for more configuration.

# Run
`docker-compose up -d`

See what containers are running on
`docker-compose ps`

Explore influxDB with CLI
`dc run influxdb-cli`
