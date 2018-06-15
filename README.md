# AmazonPay Module for WHMCS

## File structure and Insallation

 - Copy/mount ./ -> [whmcs-root]/modules/gateways/AmazonPay
 - Create a symlink AmazonPay/amazonpay.php -> [whmcs-root]/modules/gateways/amazonpay.php ->  [`cd [whmcs-root]/modules/gateways/; ln -s AmazonPay/amazonpay.php amazonpay.php`
 - Callback is at AmazonPay/callback.php

## Setup

- Enable Gateway `Amazon Pay` Under WHMCS
- Fill in the parameters
- Set `Allowed Return URL` in Amazon's merchant interface as `[whmcs-root]/modules/gateways/callback/amazonpay.php`
