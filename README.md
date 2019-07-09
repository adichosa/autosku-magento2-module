# README #

Magento 2 Auto SKU generation

### What is this repository for? ###

This is used to auto-generate SKU of Products. Allowing users to configure that prefix, length and starting value for the SKU number.

### How do I get set up? ###

1. Clone the folder to app/code/ directory.
2. Execute the following commands
	* magento setup:upgrade
	* magento setup:static-content:deploy
	* magento cache:flush
	* magento cache:clean

### Configuration ###
1. Navigation
	Store > Configuration > AUTO SKU > Configuration
2. Prefix
	This field allows user to define prefix for the sku for example : SKU, A, AA
3. Start From
	This field allows the user to define the starting point of your SKU generation. For example start from : 1
4. SKU Length
	Define the length of the SKU. For example 5 > A0001, SKU01, etc...
