# vppcfg Check Action

Run [vppcfg](https://git.ipng.ch/ipng/vppcfg) check.

## Usage

```
    - uses: actions/checkout@v4
    - name: vppcfg check
      uses: james-otten/vppcfg-check-action@main
      with:
        config-file: config.yml
        vppcfg-ref: "main"
```

## Options

| Input  | Description | Required |
| :---       |     :---     |    :---:   |
| `config-file` | VPP config file to test | Required
| `schema-file` | Schema file other than the builtin one to use | Optional
| `vppcfg-ref` | Ref of vppcfg to install. Default `main` | Optional
