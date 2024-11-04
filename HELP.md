# Native test

```yaml
Runtime: provided.al2023
```

```
sam deploy -t target/sam.native.yaml -g --profile sec

```

```text

2024-11-04T13:39:26.554Z
INIT_START Runtime Version: provided:al2023.v40 Runtime Version ARN: 
2024-11-04T13:39:26.944Z
__ ____ __ _____ ___ __ ____ ______
2024-11-04T13:39:26.944Z
--/ __ \/ / / / _ | / _ \/ //_/ / / / __/
2024-11-04T13:39:26.944Z
-/ /_/ / /_/ / __ |/ , _/ ,< / /_/ /\ \
2024-11-04T13:39:26.944Z
--\___\_\____/_/ |_/_/|_/_/|_|\____/___/
2024-11-04T13:39:26.944Z
2024-11-04 13:39:26,944 INFO [io.quarkus] (main) ntest 0.0.1 native (powered by Quarkus 3.15.1) started in 0.190s.
2024-11-04T13:39:26.944Z
2024-11-04 13:39:26,944 INFO [io.quarkus] (main) Profile prod activated.
2024-11-04T13:39:26.944Z
2024-11-04 13:39:26,944 INFO [io.quarkus] (main) Installed features: [amazon-lambda, cdi, resteasy, security, smallrye-context-propagation, vertx]
2024-11-04T13:39:26.946Z
START RequestId: da011a65-4cf9-4129-b879-9e098136355e Version: $LATEST
2024-11-04T13:39:27.385Z
END RequestId: da011a65-4cf9-4129-b879-9e098136355e
2024-11-04T13:39:27.385Z
REPORT RequestId: da011a65-4cf9-4129-b879-9e098136355e	Duration: 439.06 ms	Billed Duration: 831 ms	Memory Size: 128 MB	Max Memory Used: 67 MB	Init Duration: 391.13 ms
```