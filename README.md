# Disclaimer

I'm not the creator od these dashboards. 
I simply needed a unified way to include dashboards in victoria-k8s-stack values - file inclusion does not work as the file would have to be in subcharts (grafana) root dir.
But grafana is used as subchart in this particular case, so ...
This is just the way how to get the dashboard available from some URL for charts which are not available on grafana website, or as a plain json on github.
Exampe: https://github.com/rabbitmq/cluster-operator/blob/main/observability/grafana/dashboards/rabbitmq-queue.yml
Its a configmap, unavailable as simple json and also not available on grafana website.
