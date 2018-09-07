Terraform-OpenNebula-Docker
===========================

This is a collection of Dockerfiles that build upon the official terraform image by Hashicorp (including the build-tools of the 'full' version). The Docker image on Dockerhub is automatically updated when either one of the providers or Terraform itself is updated.

Additionally the OpenNebula provider by one of the following developers is pulled and installed:

| Dockerfile Location                                                                                                        | Description                                                                                                                                                                                                                                    |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [runtastic-provider](https://github.com/ImmoweltGroup/terraform-opennebula-provider-docker/tree/master/runtastic-provider) | The initial provider originally created by *Runtastic*. Supports most of the functionality required to control OpenNebula with Terraform Resources. Uses OpenNebula's templating language for configuration of VMs.                            |
| [immowelt-provider](https://github.com/ImmoweltGroup/terraform-opennebula-provider-docker/tree/master/immowelt-provider)   | A fork of the *runtastic-provider* that puts an abstraction layer on top of the OpenNebula templating language. Supports resource attributes to configure VMs. Actively maintained by *Immowelt Group* and taking Issues and feature requests. |

Please refer to one of the provider subfolders for information on that Dockerfile.

Collaborators
-------------

- Leroy Förster
- Florian Grothe
- Dennis Kribl

Links
-----

- this [Dockerhub](https://hub.docker.com/r/gersilex/terraform-opennebula/) [GitHub](https://github.com/gersilex/terraform-opennebula-provider-docker)
- Hashicorp's Terraform [Dockerhub](https://hub.docker.com/r/hashicorp/terraform/) [GitHub](https://github.com/hashicorp/docker-hub-images/blob/master/terraform/Dockerfile-full)
- OpenNebula [Website](https://opennebula.org/) [GitHub](https://github.com/OpenNebula/one)

License
-------

Released under the MIT License.
