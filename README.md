Field Group Table with fields in columns
=================

Extends <a href="https://drupal.org/project/field_group">Field Group</a> module with an option to make a 'Table Columns' group for viewing mode.  
Children fields will be displayed in per columns look.

##Other module
**Field Group Table** display one field by line (https://www.drupal.org/project/field_group_table).

##Requirements
<a href="https://drupal.org/project/field_group">Field Group</a>

##Installation
Like a normal Drupal module, copy folder in the right place and activate it.  
Best practice for installing is <a href="https://www.drupal.org/node/1897420">here</a>.

With composer:

    composer require drupal/table_field_group

##Configuration
In content type, "Manage Display": just create a group of type: 'Table Columns'.
In the group settings, you can wrap the table in a
* container: invisible wrapper
* fieldset: normal wrapper
* details: collapsible wrapper

