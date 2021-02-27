# Xenios Payments Cryptocurrency Gateway osCommerce

Installation: https://forgingblock.io/oscommerce2
Plugin name is: Xenios Payments Cryptocurrency osCommerce


<h2 id="integrations-oscommerce">Integration OsCommerce 2</h2>

* [Download plugin]
* Unzip archive inside osCommerce installation root folder (catalog) and change rights on extracted files accordingly to your root folder owner (for ex. `chown -R /var/www/oscommerce/ www-data:www-data`)
* After Installation go to `Modules ->  Payment -> Xenios Payments Cryptocurrency Gateway osCommerce` inside OsCommerce panel and click `Install Module` button
* In plugin settings near `Environment`, select Live (`https://api.forgingblock.io`) or Test (`https://api-demo.forgingblock.io`)
* `Do you want to accept ForginBlock payments` select `True`
* Type in your trade agreement in `Trade ID` and token inside `Token` (those details are provided to you after every new store creation in the response and inside email)
* Thats it! Your users could pay using cryptocurrency now!
