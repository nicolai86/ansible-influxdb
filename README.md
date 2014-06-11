InfluxDB
========

Install [InfluxDB](http://influxdb.org/) time series database

Role Variables
--------------

`defaults/main.yml`

| Name                        | Default Value | Description                                                      |
|-----------------------------|---------------|------------------------------------------------------------------|
| influxdb_version            | latest        | Version to install                                               |
| influxdb_seed_servers       | []            | List of host:port to use as cluster seed servers                 |
| influxdb_replication_factor | 1             | How many servers in the cluster should have a copy of each shard |

Example usage
-------------

The examples folder contains an example vagrant setup which installs & configures influxdb

License
-------

MIT

Author Information
------------------

Benjamin Curtis <benjamin.curtis@gmail.com>
Raphael Randschau <nicolai86@me.com>
