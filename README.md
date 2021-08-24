# aws-utilities

AWS Utilities

## CLI

### Setup

```
cd cli
```

### Get Private IP Address of a Site

```
# ASGType: backend | cache-queue

# NonProd
./get-ip --type <ASGType> --profile athena <siteName>

# Prod
./get-ip --type <ASGType> --profile prod <siteName>
```

### Athena Site Utility

> List all of Sites

```
# NonProd
./athena-site list

# Prod
./athena-site list prod
```

> Get Site Information

```
# NonProd
./athena-site info --siteName <siteName>

# Prod
./athena-site info prod --siteName <siteName>
```
