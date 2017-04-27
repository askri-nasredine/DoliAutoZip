## DoliAutoZip ##
### External Dolibarr Module for FRANCE, TUNISIE zip code autofill ###


**Contributors:** www.KB2i.com
**Tags:**               dolibarr, france zipcode, tunisie zipcode                  
**Plugin contact:**         askri.nasredinne@gmail.com
**Requires at least:**  5.0.0  
**Tested up to:**       5.0.1  
**License:**            GPL-3.0+  
**License URI:**        http://www.gnu.org/licenses/gpl-3.0.html


### Description ###
external Dolibarr Module, Autofill zip code for Dolibarr

### Features ###

**Dolibarr to WooCommerce**

* Periodic sync of products informations including images and stock informations
* Link customers to existing thirdparties

**WooCommerce to Dolibarr**

* Create thirdparties
* Create customer orders

**Known missing (TODO)**

* Products stock informations resync on orders
* Invoicing
* Payments
* Multiple languages products management

**Known issues**

WooCommerce VAT management vastly differs from Dolibarr and we need equivalence tables.  
Supplied tables:
* Chile
* France
* Germany
* Italy
* Spain
All other countries are missing. Contributions welcome!

### Requirements ###
** Dolibarr 5.0 **

## Installation ##

1. Make sure the WooCommerce plugin is installed into your WordPress
2. Extract the zip file to the 'wp-content/plugins/' directory of your WordPress installation
3. Activate the plugin from 'Plugins' WordPress settings page
4. Go to 'WooCommerce' 'Settings' under the 'Integration' tab and configure the 'Doliwoo' section 

## Screenshots ##

### 1. The configuration page ###
![The configuration page](assets/screenshot-1.png)


## Changelog ##

### 1.0.2 ###

* Even better logging
* Fixed thirdparties creation (prevented Dolibarr order crea
