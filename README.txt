
--------------------------------------------------------------------------------
                                 Rules Search
--------------------------------------------------------------------------------

Maintainers:
 * Ron Cohen (bluetegu), ronc@ieee.org

Adds a search box for rules in the rules and components tabs. This utility is
useful if you have many rules and components and you need to quickly find the 
ones that triggered an action, e.g. search for a rule that sent an email by a 
snippet of the text in the email sent.

Installation
------------

 * Copy the whole rules_search directory to your modules directory
   (e.g. DRUPAL_ROOT/sites/all/modules) and activate the module.
 * A search box should be available on admin/config/workflow/rules
   and admin/config/workflow/rules/components
 * The block named 'Search rules' can be configured at admin/structure/blocks

Limitations
-----------

 * Search is case sensitive

