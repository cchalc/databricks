
## End to End [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/workspace/) workspace provisioning, setup and configuration.

### Public BLOG:
- Please make sure to go thru this [blog](https://databricks.com/blog/2020/09/16/automate-azure-databricks-platform-provisioning-and-configuration.html) as it will help you understand the scope of this collection

### Pre-requistes:
- [Azure Service Principal](https://docs.microsoft.com/en-us/azure/active-directory/develop/app-objects-and-service-principals)
    Please keep aside service principal as we plan to use it with our API calls
    - client_id
    - client_secret
- [Azure Resource Group](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal#what-is-a-resource-group)
- [AAD Contributor](https://docs.microsoft.com/en-us/azure/role-based-access-control/built-in-roles#contributor) role assigned to `service principal` on `resource group` used to deploy `azure databricks workspace`

### Modules:
- Provisioning Workspace
- Authentication
- Users and Groups Management
- Cluster Policies & Permissions
- Secure acess to workspace within corporate network (IP Access List)
- Databricks Access Token Management



