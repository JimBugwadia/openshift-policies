# openshift-policies

Kyverno policies for OpenShift

Some initial ideas (thanks Andrew!):

* [ ] Disallow the use of non HTTPS OpenShift Routes
* [ ] Disallow the use of the SecurityContextConstraint (SCC) anyuid which allows a pod to run with the UID as declared in the image instead of a random UID
* [ ] Disallow binding to the self-provisioners ClusterRoleBinding
* [ ] By enabling access, resources associated with this policy have the ability to create Projects
* [ ] Disallow Jenkins Pipeline Build Strategy for OpenShift Builds. Deprecated in favor of Tekton
* [ ] Disallow the use of OpenShift RBAC API groups. Functionality has been upstreamed to Kubernetes RBAC
* [ ] Enforce etcd encryption on OpenShift ApiServer
