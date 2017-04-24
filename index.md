This is a breakdown of UI Features between Enterprise [Chef Manage](https://docs.chef.io/manage.html) and [The Foreman](https://www.theforeman.org/) with the [Chef Plugin](https://www.theforeman.org/plugins/foreman_chef/0.5/index.html)

-   All the features in Chef Manage and Show where they are in The Formeman w/ Chef Plugin, annotate if feature does not exist within The Foreman
-   All the Features in The Foreman w/ Chef Plugin that are not in Chef Manage, annotate appropriately

## Basic Interface

| Feature |                                             Chef Manage                                              |                                               The Foreman                                               | Notes |
| ------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ----- |
| Login   | <a href='/img/basic_chef_login.png'><img src="/img/basic_chef_login.png" style="width: 150px;"/></a> | <a href='/img/basic_chef_login.png'><img src="/img/basic_foreman_login.png" style="width: 150px;"/></a> | n/a   |

## Nodes

|         Feature         |                                                          Chef Manage                                                           |                                                          The Foreman                                                           | Notes |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ----- |
| Overview                | <a href='/img/nodes_chef_overview.png'><img src="/img/nodes_chef_overview.png" style="width: 150px;"/></a>                     | <a href='/img/nodes_foreman_overview.png'><img src="/img/nodes_foreman_overview.png" style="width: 150px;"/></a>               |       |
| Info/Edit - Details     | <a href='/img/nodes_chef_details.png'><img src="/img/nodes_chef_details.png" style="width: 150px;"/></a>                       | <a href='/img/nodes_foreman_details.png'><img src="/img/nodes_foreman_details.png" style="width: 150px;"/></a>                 |       |
| Info - Attributes       | <a href='/img/nodes_foreman_info_attributes.png'><img src="/img/nodes_foreman_info_attributes.png" style="width: 150px;"/></a> | <a href='/img/nodes_foreman_info_attributes.png'><img src="/img/nodes_foreman_info_attributes.png" style="width: 150px;"/></a> |       |
| Edit - Attributes       | <a href='/img/nodes_chef_edit_attributes.png'><img src="/img/nodes_chef_edit_attributes.png" style="width: 150px;"/></a>       | <a href='/img/nodes_foreman_edit_attributes.png'><img src="/img/nodes_foreman_edit_attributes.png" style="width: 150px;"/></a> |       |
| Info/Edit - Permissions | <a href='/img/nodes_chef_permissions.png'><img src="/img/nodes_chef_permissions.png" style="width: 150px;"/></a>               | <a href='/img/nodes_foreman_permissions.png'><img src="/img/nodes_foreman_permissions.png" style="width: 150px;"/></a>         |       |
| Info - Run List         | <a href='/img/nodes_chef_info_runlist.png'><img src="/img/nodes_chef_info_runlist.png" style="width: 150px;"/></a>             | <a href='/img/nodes_foreman_info_runlist.png'><img src="/img/nodes_foreman_info_runlist.png" style="width: 150px;"/></a>       |       |
| Edit - Run List         | <a href='/img/nodes_chef_edit_runlist.png'><img src="/img/nodes_chef_edit_runlist.png" style="width: 150px;"/></a>             | <a href='/img/nodes_foreman_edit_runlist.png'><img src="/img/nodes_foreman_edit_runlist.png" style="width: 150px;"/></a>       |       |



## Reports

|   Feature    |                                                 Chef Manage                                                  |                                                    The Foreman                                                     | Notes |
| ------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ----- |
| Overview      | <a href='/img/reports_chef_overview.png'><img src="/img/reports_chef_overview.png" style="width: 150px;"/></a> | <a href='/img/reports_foreman_overview.png'><img src="/img/reports_foreman_overview.png" style="width: 150px;"/></a> |       |
| History      | <a href='/img/reports_chef_history.png'><img src="/img/reports_chef_history.png" style="width: 150px;"/></a> | <a href='/img/reports_foreman_history.png'><img src="/img/reports_foreman_history.png" style="width: 150px;"/></a> |       |
| Error        | <a href='/img/reports_chef_error.png'><img src="/img/reports_chef_error.png" style="width: 150px;"/></a>     | <a href='/img/reports_foreman_error.png'><img src="/img/reports_foreman_error.png" style="width: 150px;"/></a>     |       |
| Changes/Diff | <a href='/img/reports_chef_changes.png'><img src="/img/reports_chef_changes.png" style="width: 150px;"/></a> | <a href='/img/reports_foreman_changes.png'><img src="/img/reports_foreman_changes.png" style="width: 150px;"/></a> |       |


## Policy

|   Feature    |                                                     Chef Manage                                                      |                                                        The Foreman                                                         | Notes |
| ------------ | -------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ----- |
| Cookbooks    | <a href='/img/policy_chef_cookbooks.png'><img src="/img/policy_chef_cookbooks.png" style="width: 150px;"/></a>       | <a href='/img/policy_foreman_cookbooks.png'><img src="/img/policy_foreman_cookbooks.png" style="width: 150px;"/></a>       |       |
| Roles        | <a href='/img/policy_chef_roles.png'><img src="/img/policy_chef_roles.png" style="width: 150px;"/></a>               | <a href='/img/policy_foreman_roles.png'><img src="/img/policy_foreman_roles.png" style="width: 150px;"/></a>               |       |
| Databag      | <a href='/img/policy_chef_databags.png'><img src="/img/policy_chef_databags.png" style="width: 150px;"/></a>         | <a href='/img/policy_foreman_databags.png'><img src="/img/policy_foreman_databags.png" style="width: 150px;"/></a>         |       |
| Environments | <a href='/img/policy_chef_environments.png'><img src="/img/policy_chef_environments.png" style="width: 150px;"/></a> | <a href='/img/policy_foreman_environments.png'><img src="/img/policy_foreman_environments.png" style="width: 150px;"/></a> |       |
| Clients      | <a href='/img/policy_chef_clients.png'><img src="/img/policy_chef_clients.png" style="width: 150px;"/></a>           | <a href='/img/policy_foreman_clients.png'><img src="/img/policy_foreman_clients.png" style="width: 150px;"/></a>           |       |


## Administration

|      Feature       |                                              Chef Manage                                               |                                                 The Foreman                                                  | Notes |
| ------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ----- |
| Organizations      | <a href='/img/admin_chef_orgs.png'><img src="/img/admin_chef_orgs.png" style="width: 150px;"/></a>     | <a href='/img/admin_foreman_orgs.png'><img src="/img/admin_foreman_orgs.png" style="width: 150px;"/></a>     |       |
| Users              | <a href='/img/admin_chef_users.png'><img src="/img/admin_chef_users.png" style="width: 150px;"/></a>   | <a href='/img/admin_foreman_users.png'><img src="/img/admin_foreman_users.png" style="width: 150px;"/></a>   |       |
| Groups             | <a href='/img/admin_chef_groups.png'><img src="/img/admin_chef_groups.png" style="width: 150px;"/></a> | <a href='/img/admin_foreman_groups.png'><img src="/img/admin_foreman_groups.png" style="width: 150px;"/></a> |       |
| Global Permissions | <a href='/img/admin_chef_global.png'><img src="/img/admin_chef_global.png" style="width: 150px;"/></a> | <a href='/img/admin_foreman_global.png'><img src="/img/admin_foreman_global.png" style="width: 150px;"/></a> |       |
