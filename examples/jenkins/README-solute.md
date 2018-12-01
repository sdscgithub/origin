# Example run on local origin cluster

```

  748  oc login -u developer https://ocp-1.192.168.122.100.nip.io:8443
  749  oc status
  750  oc new-project test
  751  oc new-app jenkins-persistent
  752  oc status
  753  oc get route
  754  oc get svc

```

