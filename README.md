# Cert-manager-routes-templates

Template to deploy openshift-cert-manager-routes operator in Openshift clusters

## Notes

- This operator needs to be deployed within the same namespace of cert-manager operator. As we use
  RedHat's cert-manager-operator to deploy cert-manager, the namespace is `openshift-cert-manager`
