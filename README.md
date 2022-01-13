# Custom Renovate Shareable configurations

A set of pre-configured Renovate configurations.
To reuse, prepare your `renovate.json` as follows:

```json
{
  "extends": [
      "github>DanySK/renovate-config:file-name"
  ]
}
```

Replace `file-name` with the configuration you want to inherit from, or remove `:file-name` simply use `renovate-config` to refer to `default.json`

