This is ann OpenShift template that allows for adding phppgadmin to a project that already runs postgres databased.

simply add the template to Openshift:
oc create -f phppgadmin.yaml

Then instantiate it via the web console or via
oc process phppgadmin.yaml | oc create -f -
