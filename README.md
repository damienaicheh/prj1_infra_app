# README

To run CI/CD you must:

Add the backend values to the secrets:

```bash
TFSTATE_STORAGE_ACCOUNT_NAME
TFSTATE_STORAGE_CONTAINER_NAME
TFSTATE_KEY
TFSTATE_RESOURCES_GROUP_NAME
```

## With Service Principal Name (SPN)

Create an SPN with the Storage Blob Data Owner role on the storage account.

On the GitHub repository add SPN credentials:

```bash
ARM_SPN_CLIENT_ID
ARM_SPN_CLIENT_SECRET
ARM_SUBSCRIPTION_ID
ARM_TENANT_ID
```

