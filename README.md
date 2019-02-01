# Node 10 Alpine + Yeoman + Git + Bash

This image comes to resolve an issue with Yeoman which makes it extremely difficult (almost impossible) to run as `root` or as a non-privelged user (i.e. `node`) inside a Docker container when the host is setup with *subuid* and *subgid* mappings.
