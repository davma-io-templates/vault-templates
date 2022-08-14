# Vault

HashiCorp Vault is an identity-based secrets and encryption management system.

[![Build and push images](https://github.com/davma-io-images/vault-ui/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/vault-ui/actions/workflows/docker-image.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/davma/vault-ui?logo=docker&logoColor=white)](https://hub.docker.com/r/davma/vault-ui)
[![Update application to Napptive Playground](https://github.com/davma-io-templates/vault-templates/actions/workflows/napptive-push.yml/badge.svg)](https://github.com/davma-io-templates/vault-templates/actions/workflows/napptive-push.yml)

## Requirements

Need one of the following requirements to get started

 - [K8s cluster](https://kubernetes.io/docs/tasks/tools/)

 - [Docker](https://docs.docker.com/install) / [Docker Compose](https://docs.docker.com/compose/install)

 - Free account on [NAPPTIVE platform](https://napptive.com/)

## Clone repository

Clone the repository with the following command:
````
git clone https://github.com/davma-io-templates/vault-templates.git
````

## Vault Deployment

Navigate through the cloned repository to the directory that corresponds to your prepared environment and follow the instructions.

## How to access to Vault

In a local environment you must access through ``localhost:[port]``

The davmaio-vault instance in [Napptive](https://napptive.com/) automatically gets a public URL in the form of:

```
https://davmaio-vault-<active-namespace>.apps.playground.napptive.dev
```

## References

* https://www.vaultproject.io/docs
* https://learn.hashicorp.com/vault
* https://learn.hashicorp.com/collections/vault/getting-started-ui
* https://docs.docker.com/install
* https://docs.docker.com/compose/install
* https://kubernetes.io/docs/home/