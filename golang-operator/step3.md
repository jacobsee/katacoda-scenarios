# API & Controller Initialization

To do any real work though, we need to create an API resource with

```bash
operator-sdk create api --group servers --version v1alpha1 --kind Webserver --resource --controller
```{{execute}}

And now there are some really interesting things to look through!
Since we've created a `Webserver` resource type, there are two new notable files to look at - the API definition in `api/v1alpha1/webserver_types.go`, and the controller logic in `controllers/webserver_controller.go`.