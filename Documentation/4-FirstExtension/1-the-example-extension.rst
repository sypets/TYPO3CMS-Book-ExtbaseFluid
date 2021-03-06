.. review information:
   - language: ok (corrected May/14 2019)

.. include:: ../Includes.txt

=====================
The Example Extension
=====================

Our first extension will show an inventory list of products, which we
created before in a backend list-module. Each product is marked by a title,
a short description and a quantity as the number of pieces in stock. The
following steps are necessary for implementation:

#. Create directory tree and the minimal configuration files
#. Translate the problem domain in an abstract domain model
#. Configuration of persistence layer

   * Definition of database tables
   * Configure the display of backend forms
   * Create repositories for product objects

#. Define the application flow inside the extension (create *controller* and *action* methods)
#. Implement view with Fluid
#. Configure the plugin for list display
#. Install and test the extension

.. tip::

   We choose the order above for didactic reasons. After gathering the first experience in programming
   with Extbase, you probably will work in a differnt and quicker order.
   As an alternative, you can also use the 
   `Extension Builder <https://github.com/FriendsOfTYPO3/extension_builder>`__.

