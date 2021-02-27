# Xenios Payments Cryptocurrency Gateway Magento

Installation: https://forgingblock.io/magento2
Plugin name is: Xenios Payments Cryptocurrency Gateway Magento

* [Download plugin]
* Unzip archive inside magento installation root folder and change rights on extracted files accordingly to your root folder owner (for ex. `chown -R /var/www/magento2/ www-data:www-data`)
* Run set of the commands with `magento` binary (located in `bin` folder inside magento installation root)
     - `magento module:enable ForgingBlock_Payment --clear-static-content`
	 - `magento setup:upgrade`
	 - `magento setup:static-content:deploy -f`
	 - `magento cache:clean`
* After Installation go to `Stores ->  Configuration -> Sales -> Payment Methods -> Xenios Payments Cryptocurrency Gateway Magento` inside Magento Admin panel and click expand icon
* In plugin settings near `Test Mode`, select No (`https://api.forgingblock.io`) or Yes (`https://api-demo.forgingblock.io`)
* Type in your trade agreement in `Trade ID` and token inside `Token` (those details are provided to you after every new store creation in the response and inside email)
* Click `Save Config` button
* Thats it! Your users could pay using cryptocurrency now!
