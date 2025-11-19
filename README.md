# Initial release of the full portable monitoring including:
- Grafana OSS
- InfluxDB
- Telegraf
- Speedtest CLI

# First Step
- running grafana-server and open web http://localhost:3000
- running influxd and open web http://localhost:8086
- 
# For Testing 
telegraf.exe --config telegraf.conf --test

# Manual Running
telegraf.exe --config telegraf.conf

# Automatic running all
run Start Service.bat
