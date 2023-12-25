mkdir -p /opt/yml
mkdir -p /opt/prometheus
mkdir -p /opt/prometheus/config
chown -R 1000:1000 /opt/yml
chown -R 1000:1000 /opt/prometheus
chmod -R 777 /opt/yml
chmod -R 777 /opt/prometheus

docker network create localdev

