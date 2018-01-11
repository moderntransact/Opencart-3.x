# Ubercart3.x
Modern Transact Ubercart 3.x plugin for Drupal 7.x

You must have a Drupal 7.x Installation with [Ubercart 3.x already configured with required modules](https://www.drupal.org/project/ubercart) before installing this plugin.

Dependency modules for this plug are:
* uc_credit
* payment

### Installation Instructions

> NOTE:  If you are uploading this file to a remote server from your local machine you will need to have FTP or SSH Credentials to install this plugin

1.  Download the Modern Transact Ubercart 3.x latest release [mt_ubercart_*.*.*.zip](https://github.com/bmartin-phd/Ubercart3.x/releases) to your local drive
2.  From your Drupal Administrator Menu, select `Modules` the click on `Install New Module`
3.  In the Install New Module screen, select `Choose File` and attch the mt_ubercart_*.*.*.zip you just downloaded and then press `Install`.
4.  Enter your FTP or SSH Credentials to install the module in your Drupal site

### Configuration Instructions

1.  From your Drupal Administrator Menu, select `Modules` then scroll down until you see the `Ubercart-Payment` panel.  Make sure the *Modern Transact* plugin is selected and then scroll all the way down and click `Save Configuration`.
2.  From your Drupal Administrator Menu, select `Store` then click on `Payment Methods` in the `Configuration` panel.
3.  The Payment Methods page lists the available payment methods available that were set up in the `Modules`.  Select the `Credit card` box and then `Save Configuration`
4.  Next, clieck on the `settings` link in the `Credit card`
5.  In the `Basic Settings` tab, choose `Modern Transact` as the Default Gateway
6.  In the `Modern Transact` tab, make sure the `Enable this payment gateway for use` is selected.
7.  In the `Modern Transact` tab, enter the merchant user API Key associated with your account.
> NOTE:  API Keys can be generated for in Test Mode which will allow you to checkout a sample Shopping Cart with a real or test credit card.  In test mode the card WILL NOT be charged.
8.  In the `Credit card fields` tab, make sure that the `Enable CVV text field on checkout form` and `Enable card owner text field on checkout form` are selected.
9.  Press `Save Configuration` to save the settings we just changed or added.  This should complete the configuration.


