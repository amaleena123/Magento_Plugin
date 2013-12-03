MOLPay Magento Plugin
=====================

###### MOLPay Plugin for Magento Community Edition ######


Requirement
-----------
Magento Version 1.7.x.x

Notes
-----
MOLPay Sdn. Bhd. is not responsible for any problems that might arise from the use of this module. 
Use at your own risk. Backup any critical data before proceeding. For any query or 
assistance, please email support@molpay.com 

Installations
-------------
- Download this plugin, Extract/Unzip the files. You will get the following files and folders under the main folder `app/`
  * `etc/modules/molpay.xml`
  * `code/local/Mage/MOLPay/`
  * `code/core/Mage/Checkout/Block/Callback.php`

- Upload or copy those file and folder into Magento root directory (installed folder) and its subdirectories<br>
  <i>This won't replace any of your Magento system core file</i>
  * `<MagentoRoot>/app/etc/modules/molpay.xml`
  * `<MagentoRoot>/app/code/local/Mage/MOLPay/`
  * `<MagentoRoot>/app/code/core/Mage/Checkout/Block/Callback.php`

- (Skip this if your magento is not hosted not in UNIX environment)
Please ensure the file permission is correct. For starting installation purpose, It's recommended to CHMOD to 777
  * `<MagentoRoot>/app/etc/modules/molpay.xml`
  * `<MagentoRoot>/app/code/local/Mage/MOLPay/`
  * `<MagentoRoot>/app/code/core/Mage/Checkout/Block/Callback.php`

- Login as Magento Store Admin, go to System > Configuration > Advanced

- Under panel Disabled Module Output, Please ensure that Mage_MOLPay module is on Enable state

- Save the advance Disabled Module Output

- Now, under SALES menu, click on the Payment Methods

- Under panel MOLPay payment method. Again, please ensure it's on enable state. Insert the MOLPay Merchant ID 
and MOLPay Verify Key and also change New order status to `pending`. Then save the config

- Test the plugin is functioning properly by making a test payment 
(You can test it with test account, You can get test account credentials from our support team)

Support
-------
Merchant Technical Support / Customer Care : support@molpay.com <br>
Sales/Reseller Enquiry : sales@molpay.com <br>
Marketing Campaign : marketing@molpay.com <br>
Channel/Partner Enquiry : channel@molpay.com <br>
Media Contact : media@molpay.com <br>
R&D and Tech-related Suggestion : technical@molpay.com <br>
Abuse Reporting : abuse@molpay.com

