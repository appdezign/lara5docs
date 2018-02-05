================================
 Routes
================================

.. contents:: Table of Contents


Frontend
================================

Special
--------------------------------

Examples:

- get:       /nl/
- rname:     special.home.show

- get:       /nl/search
- rname:     special.search.form


Menu Entities
--------------------------------

Examples:

- get:       /nl/myteam
- rname:     entity.team.index

- get:       /nl/myteam/john-doe
- rname:     entity.team.index.show


Menu Pages
--------------------------------

Examples:

- get:       /nl/about
- rname:     entity.page.show.123

The page ID is added in the NAMED ROUTE
because we do not have the actual Page slug in the menu route itself


Memu Forms
--------------------------------

Examples:

+---------+-----------------------+------------------------------+
| Type    | Uri                   | Route name                   |
+=========+=======================+==============================+
| get     | /nl/subscribe         | ``form.newsletter.form``     |
+---------+-----------------------+------------------------------+
| post    | /nl/ajax/subscribe    | ``ajax.newsletter.process``  |
+---------+-----------------------+------------------------------+



Fixed Entities
--------------------------------

Examples:

- get:       /nl/content/team
- rname:     content.team.index

- get:       /nl/content/team/john-doe
- rname:     content.team.index.show

Using a fixed prefix ('content'), we can reach all entities and entity objects
without using the user-defined menu


Catch All
--------------------------------

- get:       /nl/whatever
- rname:     (none)

Find menu folders and pages that ar not in the menu (orphans)



Backend
================================
