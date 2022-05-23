# tools-config-action

this action can be used to install or setup the followings:
 - kubectl install and add bitnami and stable repos
 - helm 
 - helm secrets plugin install
 - docker login
 - az login
 - skaffold install
 - sops install

and require the following inputs:
- REGISTRY_USERNAME:
    description: 'Docker registry username'
    required: true
- REGISTRY_PASSWORD:
    description: 'Docker registry password'
    required: true
- CLIENT_KEY:
    description: 'Cloud client key'
    required: true
- CLIENT_SECRET:
    description: 'Cloud client secret'
    required: true
- TENANT_ID:
    description: 'Cloud tenant ID'
    required: true