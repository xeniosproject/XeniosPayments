# Xenios Payments Cryptocurrency Gateway Zen Cart

Installation: https://forgingblock.io/zencart
Plugin name is: Xenios Payments Cryptocurrency Zen Cart


<h2 id="integrations-zencart">Integration with Zen Cart</h2>

* [Download plugin]
* Unzip archive inside zencart installation root folder and change rights on extracted files accordingly to your root folder owner (for ex. `chown -R /var/www/zencart/ www-data:www-data`)
* After Installation go to `Modules ->  Payment -> Xenios Payments Cryptocurrency Gateway Zen Cart` inside Zen Cart Admin panel and click `Edit` button
* In plugin settings near `Environment`, select Live (`https://api.forgingblock.io`) or Test (`https://api-demo.forgingblock.io`)
* In plugin settings near `Payment Zone`, select `--none--`
* Type in your trade agreement in `Trade ID` and token inside `Token` (those details are provided to you after every new store creation in the response and inside email)
* Click `Update` button
* Thats it! Your users could pay using cryptocurrency now!
