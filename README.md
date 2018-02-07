# AmazonPay Module for WHMCS

## File structure
[whmcs-root]/modules/gateways/  
                             |- AmazonPay  
                             |- amazonpay.php  
                             |- callback/amazonpay.php
 
## Setup

- Enable Gateway `Amazon Pay` Under WHMCS
- Fill in the parameters
- Set `Allowed Return URL` in Amazon's merchant interface as `[whmcs-root]/modules/gateways/callback/amazonpay.php`
