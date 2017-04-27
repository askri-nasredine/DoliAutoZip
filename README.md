## DoliAutoZip ##
### External Dolibarr Module for FRANCE, TUNISIE zip code autofill ###

**Module Contact:** [askri.nasredinne@gmail.com]
**Contributors:**          www.KB2i.com

**Tags:**                   dolibarr, france zipcode, tunisie zipcode                  
**Requires at least:**     5.0.0  
**Tested up to:**         5.0.1  
**License:**               GPL-3.0+  
**License URI:**           http://www.gnu.org/licenses/gpl-3.0.html

### 1. Description ###
    external Dolibarr Module, Autofill zip code for Dolibarr
### 2. Features ###
**2.a)  Known missing (TODO)**
* Update method for incorrect code from a parameterization interface 
* Select specific zipcode to specific region in precise country

**2.b) Known issues**

DoliAutoZip manage various country zip code
* Tunisie
* France
* Algeria ( soon )
* Morroco ( soon )
* Italy ( soon )
All other countries are missing. Contributions welcome!

### 3. Requirements ###
    Dolibarr 5.0 with mysql database 5.1 or Higher

### 4. Installation ###

 1. Be certain for the access rights on your operating system, especially linux
    chmod a+x DoliAutoZip.zip
  2. Extract the zip file to the 'dolibarr/htdocs' directory of web server
  3. Activate the module from Configuration -> Modules page
  4. Go to 'DoliAutoZip' 'Settings' under the ' Configuration -> Company/Instution' tab and select the 'zip code' fill

### 5. Screenshots ###
![The screen shot](img/autofill.jpg)
### 6. The configuration page ###
![The configuration page](assets/screenshot-1.png)


### 7. Changelog ###

  **0.0.1**
* Refactor French zipcode database
* Fixed thirdparties creation (prevented Dolibarr order crea
