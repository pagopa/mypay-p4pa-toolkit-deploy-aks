# mypay-p4pa-toolkit-deploy-aks

Helm chart to deploy mypay-p4pa-toolkit into AKS

# How to add a new app

These are the steps needed to add a new app:

- insert a new folder inside the `helm/<env>/<category>` folder (e.g. `helm/dev/top/mypay-p4pa-extractor`)
- insert a new file with the same name as the app inside the `helm/_global` folder it does not matter if it is not used
