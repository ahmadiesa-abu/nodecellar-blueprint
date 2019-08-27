# Nodecellar Blueprint

This blueprint deploys a demo wine store application that is based on nodejs and mongodb using Cloudify.
Please not that there are no AutoScale / Auto heal functionality in this blueprint

## Compatibility

Tested with:
  * Cloudify 5.0.0


## Pre-installation steps

**Please note the following requirement for manager configuration.**

The required name of the agent network is `external`


Upload the required plugins:

  * [Openstack Plugin](https://github.com/cloudify-cosmo/cloudify-openstack-plugin/releases).
  * [AWSSDK Plugin](https://github.com/cloudify-incubator/cloudify-awssdk-plugin/releases).
  * [AWS Plugin](https://github.com/cloudify-cosmo/cloudify-aws-plugin/releases).
  * [GCP Plugin](https://github.com/cloudify-incubator/cloudify-gcp-plugin/releases).
  * [Azure Plugin](https://github.com/cloudify-incubator/cloudify-azure-plugin/releases).
  * [Utilities Plugin](https://github.com/cloudify-incubator/cloudify-utilities-plugin/releases).

_Check the blueprint for the latest version of the plugin._

Install the relevant example network blueprint for the IaaS that you wish to deploy on:

  * [Openstack Example Network](https://github.com/cloudify-examples/openstack-example-network)
  * [AWS Example Network](https://github.com/cloudify-examples/aws-example-network)
  * [GCP Example Network](https://github.com/cloudify-examples/gcp-example-network)
  * [Azure Example Network](https://github.com/cloudify-examples/azure-example-network)
