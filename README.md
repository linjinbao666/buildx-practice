# instruction

```bash

docker buildx build --platform linux/amd64,linux/arm64,linux/arm -t docker.io/linjinbao66/buildx-practice:0.0.1 -o type=registry .

docker buildx build --platform linux/amd64,linux/arm64,linux/arm -o type=oci,dest=/tmp/test-oci.tar .

```

