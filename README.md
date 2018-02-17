## Configuration

- `os_image`: the name or id of the image used to provision your
  Docker host.  The playbooks expect a recent Fedora image.

- `os_key_name`: the name of the Nova keypair that you will use for
  authenticating to the Docker host.

- `os_flavor`: the name or id of the Nova flavor to be used for
  provisioning the Docker host.

- `os_networks`: a list of network names or ids to which the Docker
  host will be attached.

- `os_security_groups`: a list of security groups or ids to which the
  Docker host will be assigned.

- `os_public_network`: the name or id of a public network from which a
  floating ip will be allocated.

- `docker_group`: value for the `group` option in `daemon.json`
  (default `docker`).
