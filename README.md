
Additional features
===================

ghcr.io/thefunny42/features/k8s-tools
-------------------------------------

Install docker, helm, kubectl and optionally telepresence on alpine based images.

``telepresence``: boolean, default to false.

Release features
----------------

1. First login to ghcr.io with docker.

2. Run:

   ```sh
   devcontainer features publish  -r ghcr.io -n thefunny42/features src
   ```
