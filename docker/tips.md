## Some containers have the restarting policy set to "always", how can we stop such containers?
We can change the restart policy for that container.

```shell
docker update --restart=no my-container
```