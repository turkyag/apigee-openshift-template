# apigee-openshift-template

Apply this Apigee template on your openshift cluster

requires creation of apigee service account and priviliged scc added to it.

oc create sa apigee-sa
oc adm policy add-scc-to-user privileged -z apigee-sa
