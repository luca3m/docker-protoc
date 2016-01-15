Docker image with latest protobuf version. Currently version is 2.5.0

Use it in this way:

```
docker run -it --rm -v $PWD:/protos protoc <arguments> <yourprotofile>.proto
```
