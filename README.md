# Microservice Helm Demo

## Repository dedicated to using helm charts to deploy a complete set of microservices for one application

### Forked from https://github.com/rikg215/microservices-demo utilizing Google's "Online Boutique" demo application with 11 tiers.

### IMPLEMENTATION

**PRE-REQUISITES**
- helm
- k8s
- helmfile

1. clone repo
2. enter repo directory `cd microservices-helm-demo/`
3. run `helmfile sync`
4. profit

### UNINSTALLING

1. run `helmfile destroy` from repo directory
