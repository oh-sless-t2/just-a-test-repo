# just-a-test-repo

## Scripts

Create service principal for GitHub to use 

```bash
SUBID=""
APPNAME=""
az ad sp create-for-rbac --name $APPNAME --role contributor \
                                --scopes /subscriptions/$SUBID \
                                --sdk-auth
```


## Links

### GitHub 
https://docs.microsoft.com/en-us/azure/developer/github/connect-from-azure
