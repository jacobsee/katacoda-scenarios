# Environment Preparations

First, we will need to install the `operator-sdk`.

```sh
curl -LO https://github.com/operator-framework/operator-sdk/releases/download/v1.15.0/operator-sdk_linux_amd64

chmod +x operator-sdk_linux_amd64

sudo mv operator-sdk_linux_amd64 /usr/local/bin/operator-sdk
```{{execute}}

Then, we can run `operator-sdk version`{{execute}} to confirm that the SDK has been installed successfully and is available for our use in the terminal.
