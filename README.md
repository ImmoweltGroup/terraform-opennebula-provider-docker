Terraform-OpenNebula-Docker
===========================

This Dockerfile builds upon the official terraform image by Hashicorp (including the build-tools of the 'full' version).

Additionally the OpenNebula provider by Runtastic is pulled and installed.

Example Usage
-------------

```bash
docker run -it -v /tmp/my-terraform-code:/terraform gersilex/terraform-opennebula terraform apply
```

Collaborators
-------------

- Florian Grothe

License
-------

Released under the MIT License.
