prestashop_customer
===================

PoC drupal module for integrated login with prestashop

@todo fix logout
@todo set default TLD via a setting or derive from main
@todo refactor drupal module for consistancy in function naming / module name
@todo when user does not exist create (instead of returning error)


Some pre-requisuites have to be taken care of before this quick work

Set up drupal at the root of the TLD
Install the associated Drupal module drupal_prestashop on the Drupal site
Set config values for API key and Prestashop URL at /admin/config/system/prestashop

Setup PrestaShop  on a sub domain of the drupal install
Set value in modules/overides/classes/Cookies.php to the TLD where Drupal lives
Install the customerlogin module

