# Wordpress_Kubernetes

## Overview

In this project, you will have worked :
- WordPress
- MySQL for WordPress
- A monitoring system based on Prometheus & Grafana
- A nginx has loadbalancer / proxy

## Usage

0. Install Kubernetes, Docker & co

1. Clone the repo : `git clone https://github.com/thoomson/Wordpress_Kubernetes`

2. Install skaffold (more informations available on the official site : https://skaffold.dev/)

3. Install Helm (more informations available here: https://github.com/helm/helm)

4. Install Prometheus with Helm. You can follow this very good tutorial : https://itnext.io/kubernetes-monitoring-with-prometheus-in-15-minutes-8e54d1de2e13

5. Deploy Nginx Ingress Controller. Tutorial available here : https://kubernetes.github.io/ingress-nginx/deploy/

6. Just run : `skaffold run`

## Result

Not write yet..

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request