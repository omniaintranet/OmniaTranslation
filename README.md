# OmniaTranslation
Repository for Omnia translations automation

# Test new translated files in live environment
- Usually this is done in Production cloud, we need to sync the localizations to test cloud via triggering this pipeline [Upload Localization to Test Clouds](https://dev.azure.com/omnia-source/Omnia/_build?definitionId=295)
- After that reconcile the tenant that wants to be tested `omnia tenants reconcile [tenantid]`
