
```
docker ps -q | wc -l

docker inspect docker-id | jq .

docker ps | grep fluentd

systemctl status datadog-agent

systemctl list-units --type=service | grep -i "fluentd\|data"

```
