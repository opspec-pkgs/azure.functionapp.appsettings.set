# Problem statement
sets azure functionapp appsettings

# Example usage

> note: in examples, VERSION represents a version of the azure.functionapp.appsettings.set pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.functionapp.appsettings.set#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.functionapp.appsettings.set#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/azure.functionapp.appsettings.set#VERSION }
  inputs: 
    subscriptionId:
    loginId:
    loginSecret:
    name:
    resourceGroup:
    settings:
    # begin optional args
    loginTenantId:
    loginType:
    # end optional args
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.functionapp.appsettings.set/issues)
