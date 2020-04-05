# c2p-opencart-2.3 / cointopay.com

SOURCE CODE FOR COINTOPAY OPENCART PLUGIN LOCATED HERE: https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=37980&filter_download_id=36&sort=date_added

This is the payment module for using Cointopay (www.cointopay.com) crypto payment module on OpenCart 2.3

Upload the admin and catalog folder to your opencart installation.

Enable it in your admin panel and set api key and secret. Set your default coin and you are ready to
go after you have set return url at cointopay.com.

Under "Payment URLs"
Payment Confirmation URL : 
```
http://yourdomain.com/index.php?route=extenstion/payment/cointopay/callback&
```
Payment Fail URL : 
```
http://youdomain.com/index.php?route=extension/payment/cointopay/callback&
```

First version created by Fredrik Bodin @ www.sicanet.net (contact@sicanet.net)

Donations are welcome BTC: 1LhEdrNhu1qxCvXpQKTDVCke2494ruxZ7c
