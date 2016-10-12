# azure-management
## AppSettings
This project needs an AppSecrets.config file in the root of the AzureManagement project. The file needs to have the following settings but the values for ClientId, Domain and TenantId needs to be set:
```xml
<appSettings>
  <add key="ida:ClientId" value="" />
  <add key="ida:AADInstance" value="https://login.microsoftonline.com/" />
  <add key="ida:Domain" value="" />
  <add key="ida:TenantId" value="" />
  <add key="ida:PostLogoutRedirectUri" value="https://localhost:44381/" />
</appSettings>
```
