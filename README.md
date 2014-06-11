InfluxDB
========

Install [InfluxDB](http://influxdb.org/) time series database

Role Variables
--------------

`defaults/main.yml`

| Name                        | Default Value | Description                                                      |
|-----------------------------|---------------|------------------------------------------------------------------|
| influxdb.version            | latest        | Version to install                                               |
| influxdb.seed_servers       | []            | List of host:port to use as cluster seed servers                 |
| influxdb.replication_factor | 1             | How many servers in the cluster should have a copy of each shard |

License
-------

MIT

Author Information
------------------

Benjamin Curtis <benjamin.curtis@gmail.com>
