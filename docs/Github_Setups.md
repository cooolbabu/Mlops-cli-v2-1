## Work done in Github for Azure MLOps

### Connections

- Create a Service Principle for GitHub account and add security info project settings

~~~
 az ad sp create-for-rbac --name "github-aml-sp" --role contributor \
  --scopes /subscriptions/subscription-id/resourceGroups/rg-name \
  --sdk-auth

- Add **AZURE_CREDENTIALS** to project repo secrets

- Check_connnectivity is workflow that checks connectivity to AML workspace

