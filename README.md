# SPT-2001_GoogleCloud_StackDriver

## [Stackdriver Debugger](https://cloud.google.com/debugger/docs/quickstart#deploy_to_app_engine)
----------------
Start by deploying a Python 2.7 app to App Engine Standard.

1. Clone the project to a local repository:

```bash
git clone https://github.com/GoogleCloudPlatform/python-docs-samples
```

2. Go to the directory that contains the sample code:
```bash
cd python-docs-samples/appengine/standard/hello_world
```

3. Initialize the Google Cloud SDK with your project ID:
```bash
gcloud config set project [YOUR_PROJECT_ID]
```
4. Deploy your application:
```bash
gcloud app deploy --version=v1
```
5. Try your app by sending it a request:
```bash
gcloud app browse
```

## [Google Cloud Platform Python Samples](https://github.com/GoogleCloudPlatform/python-docs-samples)

[![Open in Cloud Shell][shell_img]][shell_link]

[shell_img]: http://gstatic.com/cloudssh/images/open-btn.png
[shell_link]: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=./README.md

This repository holds the samples used in the python documentation on [cloud.google.com](https://cloud.google.com).

[![Build Status](https://travis-ci.org/GoogleCloudPlatform/python-docs-samples.svg)](https://travis-ci.org/GoogleCloudPlatform/python-docs-samples)
[![Coverage Status](https://coveralls.io/repos/github/GoogleCloudPlatform/python-docs-samples/badge.svg?branch=HEAD)](https://coveralls.io/github/GoogleCloudPlatform/python-docs-samples?branch=HEAD)

For a more detailed introduction to a product, check the README.md in the
corresponding folder.

## Contributing changes

* See [CONTRIBUTING.md](CONTRIBUTING.md)

## Licensing

* See [LICENSE](LICENSE)
