Terraform-OpenNebula-Docker
===========================

[This Dockerfile](https://github.com/gersilex/terraform-opennebula-provider-docker/blob/master/Dockerfile) builds upon the official terraform image by Hashicorp (including the build-tools of the 'full' version).

Additionally the OpenNebula provider by ImmoweltGroup is pulled and installed.

Example Usage
-------------

```bash
docker run -it -v /tmp/my-terraform-code:/terraform gersilex/terraform-opennebula terraform apply
```

Collaborators
-------------

- Florian Grothe

Links
-----

- this [Dockerhub](https://hub.docker.com/r/gersilex/terraform-opennebula/) [GitHub](https://github.com/gersilex/terraform-opennebula-provider-docker)
- Hashicorp's Terraform [Dockerhub](https://hub.docker.com/r/hashicorp/terraform/) [GitHub](https://github.com/hashicorp/docker-hub-images/blob/master/terraform/Dockerfile-full)
- ImmoweltGroup's OpenNebula Provider [GitHub](https://github.com/immoweltgroup/terraform-provider-opennebula)
- OpenNebula [Website](https://opennebula.org/) [GitHub](https://github.com/OpenNebula/one)

License
-------

Released under the MIT License.
