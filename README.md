This example shows how the image is not exported to the artifactdir

```
$ ./debos.sh -t tarball:false example.yml
$ ls artifacts/
   nothing
$ ls
  results.img
```

If we use a pack action the compressed file is exported to the artifactdir

```
$ ./debos.sh -t tarball:true example.yml
$ ls artifacts/
  results.tar.gz
```

