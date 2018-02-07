# AmazonPay Module for WHMCS

## File structure
[whmcs-root]/modules/gateways/
 |- AmazonPay
 |- amazonpay.php
 |- callback/amazonpay-return.php
 
## Setup

- Enable Gateway `AmazonPay` Under WHMCS
- Fill in the parameters
- Set `Allowed Return URL` in Amazon's merchant interface as <whmcs-url>/modules/gateways/callback/amazonpay.php