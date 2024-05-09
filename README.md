Download Pinot server [here](https://downloads.apache.org/pinot/apache-pinot-1.1.0/apache-pinot-1.1.0-bin.tar.gz), unzip the binary and run `./bin/pinot-admin.sh QuickStart -type batch` to start Pinot server.
Run the following rill cmd from the repo to connect to Pinot server -
```
rill start --db-driver pinot --db http://localhost:9000
```
