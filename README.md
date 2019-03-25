# Using the Jeeb plugin for VirtueMart

## Prerequisites

* Last Version Tested: Joomla 2.5.20 VirtueMart 2.6.6

You must have a Jeeb merchant account to use this plugin.

## Installation
The Joomla Extension Manager expects a zip file for installation. You can download this zip file from the [most recent release](https://github.com/gdhar67/Jeeb.Virtuemart/releases) on the release page of this repository. Otherwise, the contents of the zip file can be found in the upload subdirectory. Create a zip file of everything in the upload directory and then follow the configuration instructions below.
 
## Configuration
1. Go to Extensions -> Extension Manager -> Install
2. Browse and select the zip file, click Upload & Install.
3. Go to Manage, and find the plugin under "VM Payment - Jeeb", and make sure that the plugin is enabled.
4. Go to Components -> VirtueMart and click on Payment Methods.
5. Click New and type in the information, selecting "VM Payment - Jeeb" as Payment Method. Be sure to select "Yes" in the publish section. Click save.
6. Get your signature of your merchant account from Jeeb.
7. Select the configuration tab for the payment method that you just created, and enter your API Key from step 6.
8. Select your network: livenet for real bitcoin, testnet for test bitcoin. Please double check that the website that you received your API Key from corresponds to the chosen network. 
9. Set a Base currency(it usually should be the currency of your store) and Target Currency(It is a multi-select option. You can choose any cryptocurrency from the listed options, if you want to set LTC and BTC as target currency then the text you should enter is "btc/ltc").
10. Set the language of the payment page (you can set Auto-Select to auto detecting manner).
11. Click save and close.
