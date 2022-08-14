# davma.io Vault

</br>

<img src="https://pbs.twimg.com/media/EZl8SPHWAAIamAu.jpg" alt="drawing" width="600"/>

</br>

### HashiCorp Vault is an identity-based secrets and encryption management system
</br>


[![Build and push images](https://github.com/davma-io-images/vault-ui/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/vault-ui/actions/workflows/docker-image.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/davma/vault-ui?logo=docker&logoColor=white)](https://hub.docker.com/r/davma/vault-ui) 

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for production environments__. 

For more info or help [contact](mailto:contact@davma.io).

## How to access to Vault

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the davmaio-wikijs component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-Vault
```

The davmaio-Vault instance automatically gets a public URL in the form of:

```
https://davmaio-vault-<active-namespace>.apps.playground.napptive.dev
```

You can get the full link in endpoints inside component davmaio-vault

Once the Vault UI has loaded, you should:

- Select the number of keys needed to unlock the vault.
- Download the json file with the keys.

Now you can access to unlock the vault

### You can access the most complete training on the [HashiCorp Vault website](https://learn.hashicorp.com/collections/vault/getting-started-ui)


## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.5 of cores available
- 500 Mb of ram available

## References
* https://www.vaultproject.io/docs
* https://learn.hashicorp.com/vault
* https://learn.hashicorp.com/collections/vault/getting-started-ui



</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>