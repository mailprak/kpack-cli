## kp clusterstack update

Update a cluster stack

### Synopsis

Updates the run and build images of a specific cluster-scoped stack.

The run and build images will be uploaded to the the registry configured on your stack.
Therefore, you must have credentials to access the registry on your machine.

```
kp clusterstack update <name> [flags]
```

### Examples

```
kp clusterstack update my-stack --build-image my-registry.com/build --run-image my-registry.com/run
kp clusterstack update my-stack --build-image ../path/to/build.tar --run-image ../path/to/run.tar
```

### Options

```
  -b, --build-image string   build image tag or local tar file path
  -h, --help                 help for update
  -r, --run-image string     run image tag or local tar file path
```

### SEE ALSO

* [kp clusterstack](kp_clusterstack.md)	 - Cluster Stack Commands
