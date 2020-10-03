# Firefly-iii helm chart

## Setup
Optionally, create a secret which you can reference with `existingSecret`:
`kubectl create secret generic firefly-iii --from-literal=APP_KEY= --from-literal=DB_USERNAME= --from-literal=DB_PASSWORD= --from-literal=postgresql-username= --from-literal=postgresql-password=`
