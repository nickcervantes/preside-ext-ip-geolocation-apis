# Preside IP Geolocation APIs Extension
Preside extension to allow application developers to get all geolocation information about an IP address in a number of different formats.

Mainly developed for use with the https://extreme-ip-lookup.com/ IP Geolocation service but can be adapted to another provider.

Simply configure the API settings and that should be all you need.  Examples are given in the CMS Admin Settings form.

## Installation
Install the extension to your application via either of the methods detailed below (Git submodule / CommandBox + ForgeBox)

### Git Submodule method
From the root of your application, type the following command:

	git submodule add https://github.com/nodoherty/preside-ext-ip-geolocation-apis.git application/extensions/preside-ext-ip-geolocation-apis

### CommandBox (box.json) method
From the root of your application type the following command:

	box install preside-ext-ip-geolocation-apis

From the Preside CMS developer console (using the back tick ` key) reload the application:

	reload all

### Enabling the extension
Once the files are installed, enable the extension by opening up the Preside CMS developer console and entering:

	extension enable preside-ext-ip-geolocation-apis
	reload all

## Usage
See the included handler `ipGeolocation.cfc` for examples of calling directly via ColdFusion server code or via AJAX