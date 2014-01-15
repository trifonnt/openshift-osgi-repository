# OBR repository on OpenShift

Simple way to deploy OBR (OSGi Bundle Repository) on OpenShift

```
rhc app create [app name] ruby-1.9 --from-code=https://github.com/openshift-quickstart/osgi-repository.git
```

## How to

Just edit pom.xml file so it contains all the artifacts you want to have available in your repository.

Git add, commit, push ... and the template should take care of the rest.
