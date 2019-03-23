# Azure Key Vault - Authentication
[![Build Status](https://travis-ci.org/tomkerkhove/demo-azure-key-vault-auth.svg?branch=master)](https://travis-ci.org/tomkerkhove/demo-azure-key-vault-auth)

_**I recommend using [Arcus Security](https://security.arcus-azure.net/auth/azure-key-vault) which abstracts this away from you.**_

Simple demo on how you can use Azure Key Vault and how you can authenticate.

Following operations highlight authentication mechanisms:
- `/api/v1/secrets/basic-auth/{secretName}` - Shows how you can authenticate via basic authentication
- `/api/v1/secrets/managed-service-identity/{secretName}` - Shows how you can authenticate via Azure AD Managed Service Identity (MSI)
