## Installing the Aspenmesh collector

### Paste the following commands into your terminal. Be sure to replace your api key!

    kubectl create ns aspenmesh

    helm repo add aspenmesh https://aspenmesh.github.io/aspenmesh-charts/

    helm repo update

    helm upgrade --install aspenmesh-collector aspenmesh/aspenmesh-collector -n aspenmesh --set apiKey=<YOUR-API-KEY-HERE>
