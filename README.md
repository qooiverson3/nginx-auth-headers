install
```shell
helm install ngx-lua . --set env.HEADER_SECRET_VALUE=$(echo -n "my-secret-value" | base64)
```