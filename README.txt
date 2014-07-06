About Alignet VPOS for Drupal
-----------------------------

This is a gateway payment module for Drupal, it allows it to make payments using
the services of Alignet; a gateway for many banks in the latinamerica region.

Installing Alignet VPOS
-----------------------

1. Download the PHP Kit from http://vpos.alignet.com/documentacion.html
   You can find this under the tab titled "Plugins y Componentes".
2. Unzip the contents and copy the file vpos_plugin.php into the plugins folder of the module 
   (You will find the file inside the folder titled "Plugin desofuscado PHP 5.3.x").
3. Enable the Alignet VPOS module

Configuring the Alignet VPOS
----------------------------

1. Visit admin/store/settings/payment/method/alignet_vpos_gateway
2. General Tab, input the requested information, you will get this values from the acquiring bank.
3. RSA & Vector Keys Tab
   3a. vectorKey is a random 16 hexanumber, you can generate one @ http://www.random.org/cgi-bin/randbyte?nbytes=8&format=h
   3b. RSA 1024bit keys must be generated, you can do this @ http://www.pepta.net/