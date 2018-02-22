# Homebridge-Docker-Luftdaten

Some files to get your Luftdaten-sensor up and running in Homebridge using Docker. Uses <a href="https://github.com/oznu/docker-homebridge">docker-homebridge</a> and <a href="https://www.npmjs.com/package/homebridge-airrohr">homebridge-airrohr</a>.

## Setup

```
git clone https://github.com/marma/homebridge-docker-luftdaten
cd homebridge-docker-luftdaten
```

Edit homebridge_volume/config.json to include the IP-address (or name I guess) of your sensor and sensor ID. Start the container, if all goes well you should get a QR-code to scan with your iPhone.

```
docker-compose up
```

Exit by pressing Ctrl-Cand start container again in the background.

```
docker-compose up -d
```

Done!

