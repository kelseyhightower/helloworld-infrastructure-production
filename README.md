# helloworld-infrastructure-production

This repo holds the Kubernetes configuration files for the helloworld application.

## Target Environment

Production

## Usage

Changes pushed to the master branch should trigger the following actions:

 - recursive application of the configuration files located under the kubernetes directory.

See the [cloudbuild.yaml](cloudbuild.yaml) file for more details.
