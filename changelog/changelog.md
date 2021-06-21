# Changelog

## 2.5.0 - 2021-06-19

### 2.5.1 - Hotfix for 2.5.0
[Updated files](https://gist.github.com/dimovdaniel/83e01921ebe704a0a5258387f46b1625)

### Video
{% embed url="https://youtu.be/0W8sLuBV--k" caption="" %}


### New
* Delivery cost with delivery areas
* Logo for restaurants in the header area

### Improvements
* Better SEO
* Items import
* Limit number of orders in plan

# Fixes
* Delivery address not showing in order details

### How to update
Just log in as admin, go to "Updates" and you should see new "New Update 2.5.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/fb8786456f106660b85ccbe3e58744af)

## 2.4.x - Continues updates

* 2.4.3 - Subscription fixes, Landing fixes, Import fixes  [Files](https://i.imgur.com/nmxO4ik.png)
* 2.4.2 - Local Bank fixes, decimal orders prevent, better whatsapp message [Files](https://gist.github.com/dimovdaniel/cb945997092427699ee7a811e265e61e)
* 2.4.1 - Local Bank fixes, Saving Stripe Fixes, Working Hours Fixes - [Files](https://gist.github.com/dimovdaniel/c0791ee6280805b30e1acd8eafddbb93)

## 2.4.0 - 2021-04-16

### Video

{% embed url="https://youtu.be/fkZZHYLLems" caption="" %}

### New

* Payment modules as Plug And Play
* Each payment method can be set so money from orders goes to vendor
* Restaurant management reorganization
* New Printing module
* vendors can set their own time slots intervals, prepare time and timezone

### Fixes

* Tax calculation fixes
* Lot of small fixes

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.4.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.

If you have lot of users / clients and you are using other payment method for orders than Stripe, I will recommend full project backup, database and files. Afterwords you will need to download the desired payment method, and set up the way you like it. Please look into the update video to see what has been changed in the payment methods. Restaurants will need to reset the api keys for Mollie or PayPal if they where accepting direct payments.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/71f85505b15f776f1cd2e2e5b173d2a7)

## 2.3.x Continues updates

* 2.3.2 - Support for the impressum app. [Files](https://gist.github.com/dimovdaniel/45b4b2476896e2920550ef58c33bacab)
* 2.3.1 - Fix for restaurant orders \(array\_key\_exists\(\)\) - File changed: app/Order.php

## 2.3.0 - 2021-03-17

### New

* Apps \( instal new modules via upload \)
* Free app - invoice pdf printer 
* Owner API - API endpoint for owner actions

### Fixes

* Fixes for Financial reports
* Fixes for testimonials and 
* Other small fixes

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.3.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/c1eaaacc8f36fa71ef44a4cbbdc26087)

## 2.1.x - 2.2.x Continues updates

* 2.2.3 - Fix for handling restaurant-name like aliases -[Files](https://gist.github.com/dimovdaniel/6ebd98a48eba52906fb536dfd80d45e5)
* 2.2.2 - Fixes in calculating tax, Fixes in  financial report, add new item image missing - [Files](https://gist.github.com/dimovdaniel/a63e2dbabde132691d892430199a06f9)
* 2.2.1 - Custom Fields on orders, Restaurant address improvements - [Files](https://gist.github.com/dimovdaniel/4e5e670a13bbcb52e1d1143f34752c44)
* 2.2.0 - Categories sorting, Fix for Stripe 3d secure or plan subscribe - [Files](https://gist.github.com/dimovdaniel/4e168f71933b3249a4e853e5f6995b21)
* 2.1.9 - Temporary update 
* 2.1.8 - Temporary update 
* 2.1.7 - Fix for restaurant save, Memory Limit info, Migrate in update - [Modified Files](https://gist.github.com/dimovdaniel/fcf3703ec281b69265869ad9b9953742)
* 2.1.6 - PayPal payment for restaurant, Fixes on variant show - [Modified Files](https://gist.github.com/dimovdaniel/90d555271a5db0c6f2cf7980e69befab)
* 2.1.5 - New way of updates, fixes in image upload in settings  - [Modified Files](https://gist.github.com/dimovdaniel/786c82b2776eda1d47a97a5ec9c970c4) -- \(YOU WILL GET ERROR 500 - but that is ok, since now we have new system for update \)
* 2.1.4 - WhatsApp Message is separate blade file - [Modified Files](https://gist.github.com/dimovdaniel/7a3fad29bf15241fe310fdecd8e0da68)
* 2.1.3 - Fixes in Mollie payments - [Modified Files](https://gist.github.com/dimovdaniel/644f827344deed01443309429f56a542)
* 2.1.2 - Missing Translations, Live Order fix, CSS fixes, Fix on deleting demo data -   [Modified files](https://gist.github.com/dimovdaniel/165ae8c25bbf1fce08cb5a2243127fef)

## 2.1.1  - 2021-02-10

### New

* Cookie Consent 
* Register in pop up
* GDRP on Register

### Fixes

* Live Orders Fixes

### Improvements

* Full list of currencies
* Better error 500 show

### How to update

Just log in as admin, go to "Site Settings" and on right top you should new "New Update 2.1.1". Click on the button to update.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/6b51bda8517cc0804d1c0c99196d63c8)

## 2.1.0  - Initial

