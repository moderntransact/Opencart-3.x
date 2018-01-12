# Modern Transact Opencart 3.x Plugin Installation

1.  [Download and unzip](https://github.com/moderntransact/Opencart-3.x/releases) the latest Modern Transact Opencart 3.x release to a new directory.
2.  The unzipped file provides the files required to install the Modern Transact Opencart 3.x Plugin using the same directory structure (`/admin` and `/catalog`) found in your Opencart installation.  You need to copy each these files into the corrosponding Opencart directories.
>For example, the unzipped file `admin\controller\extension\payment\moderntransact.php` needs to be copied to your Opencart server `..admin\controller\extension\payment\` folder.

# Modern Transact Opencart 3.x Plugin Setup

1.  Log into your Opencart Administrator and go to Extensions
2.  Under "Choose your Extension Type" select Payments
3.  Scroll down this list of payment plugins until you see 'Modern Transact'.  At the far right you will see an inactive edit button and a green '+'.  Click on the green '+' to install the Modern Transact plugin.
4.  Once the Modern Transact plugin is installed, The edit button should be active.  Click on this to configure your Modern Transact plugin.
* Enter your `Modern Transact API Key` *NOTE:  API Keys can be generated for in Test Mode which will allow you to checkout a sample Shopping Cart with a real or test credit card.  In test mode the card WILL NOT be charged.*
* Set the `Transaction Type` to `Sale`
* Set the `Status` of the plugin to `Enabled`
5.  Save Confguration.  The Modern Transaction Payment Gateway should be availale now at checkout.


# Releases

* [Opencart 3.x release 1.0.0 - mt_opencart3x.1.0.0.zip](https://github.com/moderntransact/Opencart-3.x/releases/download/1.0.0/mt_opencart3x.1.0.0.zip)
