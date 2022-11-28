## Install the Aspenmesh collector

    kubectl create ns aspenmesh

    helm repo add aspenmesh https://aspenmesh.github.io/aspenmesh-charts/

    helm repo update

    helm upgrade --install aspenmesh-collector aspenmesh/aspenmesh-collector -n aspenmesh --set apiKey=<YOUR-API-KEY-HERE>
