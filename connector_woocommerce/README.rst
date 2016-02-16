WooCommerce Connector
=================

This is an Open-Source connector linking Odoo and WooCommerce. It is capable to interface the following information
* Import category
* Import Product
* Import Customers 
* Import Sale Orders 

Installation
============
* Install this module in Odoo
* Install WooCommerce export module in WooCommerce/Wordpress
* Make sure the user which will configure and use the interface has following user rights. Connector: Connector Manager
* In Linux install WooCommerce Python module.

  * sudo easy_install woocommerce
  
    or
  * sudo pip install woocommerce
  * (Optional) check with command below if it went OK.
      pip freeze | grep Woo
