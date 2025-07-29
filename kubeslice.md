helm upgrade -i spire-crds charts/spire-crds \
-n spire --create-namespace

helm upgrade -i spire charts/spire \
-n spire --create-namespace \
-f val.yaml

