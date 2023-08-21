## Work done in Github for Azure MLOps

### Connections

- Create a Service Principle for GitHub account and add security info project settings

'''
az ad sp create-for-rbac --name "mslearn-azure-sp" --role contributor \
 --scopes /subscriptions/ba71910d-910d-494a-a172-8704de3618d3/resourceGroups/rg-aml-1022 \
 --sdk-auth
'''
