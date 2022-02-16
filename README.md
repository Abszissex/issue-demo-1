# issue-demo-1


### Build

```sh
bazel build //...
bazel build //src/app:app
```

### Start Redis Docker Container

```sh
docker run -p 6379:6379 --rm --name dRedis redis:6.2.6-alpine

```