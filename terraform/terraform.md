## How to install deprecated terraform provider which is not available for Apple M1 Processor
Use [m1-terraform-provider-helper](https://github.com/kreuzwerker/m1-terraform-provider-helper)
```
brew install kreuzwerker/taps/m1-terraform-provider-helper
```

## How to run terraform with debug logs
```
TF_ENABLE_API_LOGGING=1 TF_LOG=debug terraform plan
```

## Pass variable to terraform execution
```
terraform apply -var=foo="value_of_foo"
```

## Destroy resource from tf
```
terraform destroy -target RESOURCE_TYPE.NAME -target RESOURCE_TYPE2.NAME
```

