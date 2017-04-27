# ZipAutoFill FRANCE TUNISIE #
# external Dolibarr Module


**Contributors:** www.KB2i.com
**Tags:**               dolibarr, france zipcode, tunisie zipcode                  
**Plugin contact:**         askri.nasredinne@gmail.com
**Requires at least:**  5.0.0  
**Tested up to:**       5.0.1  
**License:**            GPL-3.0+  
**License URI:**        http://www.gnu.org/licenses/gpl-3.0.html


## Description ##
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

**PHP extensions**

* SOAP
* OpenSSL

**WordPress plugins**

* Woocommerce >= 2.0.0

**Dolibarr**

* HTTPS access with a valid certificate
* Dolibarr >= 3.4.0
* Modules:
    * Webservices
    * Thirdparties
    * Products
    * Categories (Products)
    * Orders

## Installation ##

1. Make sure the WooCommerce plugin is installed into your WordPress
2. Extract the zip file to the 'wp-content/plugins/' directory of your WordPress installation
3. Activate the plugin from 'Plugins' WordPress settings page
4. Go to 'WooCommerce' 'Settings' under the 'Integration' tab and configure the 'Doliwoo' section

## Frequently Asked Questions ##

### Is this plugin stable and useable in a production environment? ###

NO! This is beta code. This project started as an internal proof of concept and has just been reviewed.  
But you're very welcome to test it on a pre-production environment.

### OK, so how can I make it happen then? ###

You can help by testing, providing detailed bug reports, documentation or even code.  
**Alternatively, you can buy paid support and/or development services from us:** [GPC.solutions](https://gpcsolutions.fr).  

### Why do I need to use HTTPS with a good known SSL certificate? ###

Otherwise SOAP requests will fail.  
This is a security feature to make sure your important data is properly encrypted in transit between WooCommerce and Dolibarr.  
You may allow insecure requests by tweaking the source code if you know what you're doing but we don't recommend that.  

## Screenshots ##

### 1. The configuration page ###
![The configuration page](assets/screenshot-1.png)


## Changelog ##

### 1.0.2 ###

* Even better logging
* Fixed thirdparties creation (prevented Dolibarr order crea
