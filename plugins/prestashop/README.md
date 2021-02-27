# Xenios Payments Cryptocurrency Gateway PrestaShop

Installation: https://forgingblock.io/prestashop
Plugin name is: Xenios Payments Cryptocurrency PrestaShop

<h2 id="integrations-prestashop">Integration with PrestaShop</h2>

* [Download plugin]
* In PrestaShop admin panel select `Modules ->  Module Catalog -> Install a module` and upload zip archive
* After Installation click `Configure` or you could find plugin in `Modules ->  Module Manager -> xenios` and click `Configure`
* In plugin settings near `API URL`, select `https://api.forgingblock.io` (MainNet) or `https://api-demo.forgingblock.io` (TestNet)
* Create pairing code using [Dashboard](https://dash.forgingblock.io/), select `Accounts -> Plugins`
     - For TestNet use [TestNet Dashboard](https://dash-demo.forgingblock.io/)
     - In case you are using API directly you could use [Create pairing form](https://api.forgingblock.io/docs/#create-pairing) instead
* Copy `pairing` value you received and click `Pair`
* Thats it! Your users could pay using cryptocurrency now!
