Esta implementacion es la version kube-prometheus

https://github.com/prometheus-operator/kube-prometheus

Instalación:

Dentro de la carpeta prometheus-grafana ejecutar:

  kubectl apply --server-side -f setup -f .
  kubectl apply --server-side --force-conflicts -f setup -f .

Nota: A veces es necesario ejecutar el comando varias veces

grafana

username: admin
password: prom-operator