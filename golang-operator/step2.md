# Operator Initialization

This will be an extremely simple operator to use as a learning guide. It accepts `Webserver` custom resources, and deploys an Apache pod with a `service` and a `route` on OpenShift to access the server.

We should be starting out with an empty project folder.

From that empty folder, scaffold out an operator with

```bash
operator-sdk init --domain redhat.com --repo github.com/jacobsee/sample-operator --skip-go-version-check
```{{execute}}

Take a look around - there are some standard Go project files, and some Kubernetes manifests in the `config` directory.