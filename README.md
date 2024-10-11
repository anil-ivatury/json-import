# Custom Migrate Module

This module pulls data from the `https://jsonplaceholder.typicode.com/users` API and imports it as Drupal users and company nodes.

## Dependencies:
- `migrate`
- `migrate_plus`
- `migrate_tools`

## Configuration:
The migration uses the following configuration files:
- `custom_migrate_company.yml`: Migrates company data as nodes.
- `custom_migrate_user.yml`: Migrates users from the API and links them to company nodes.

Also created  content type  Company with fields
-field_name	
-field_catchphrase
-field_bs	
Also added fields to people (user)
-field_name
-field_phone
-field_website
-field_company
(Entity reference
Reference type: Content
Content type: Company)
Added drupal10.sql.gz as dump in root folder
