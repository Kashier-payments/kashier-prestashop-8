# kashier-prestashop-8
Kashier payment gateway support for prestashop 8.x


![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/presta-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service for egyptian merchants.

- IFrame Integration.

- 3D secure cards authentication support.

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.

- Support multiple payment methods
     
     - card 
     - wallet
     - bank installments

- Customize order state after success payment.


### Installation

- Download [kashier.zip](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/main/kashier.zip)

- Upload the plugin on prestashop from sidebar modules > Module manager > Upload a module.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/upload_module.png)

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/upload_kashier.png)


- Enable and Configure your plugin.

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > Payment API keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/apikey_mid_test.png)

- Insert the MID and Test Api Key in the Configuration page of the module.

- Make sure the test mode is on.

- select your payment methods.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/module_configuration_test.png)

### Test plugin 

- Proceed to make an order on your shop, a new payment method is added "Pay by card". it could be changed from module configuration.

- After proceeding you will find a Kashier "pay now" button, fill in the test card and proceed to make a payment.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/module_test_payment_1.png)

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/module_test_payment_2.png)


### Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > Payment API Keys

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/apikey_mid_live.png)

- Insert Live Api Key in the Configuration page of the module.

- Remove the test mode check.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.7/master/steps/module_configuration_live.png)

### Support
##### Success Order state change

- You could choose the success order state change call back from the module configuration. you will find your states for the success order state and click save.

##### Enable and disable currency
- If there is a currency not supported by kashier, you could just disable it from "Payments > ".

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/Enable_and_disable_kashier_on_currencies.png)

### Notes

- Make sure to disable "Performance > Advanced performance parameters > Move javascript to the end", if the IFrame button is not visible.

- Leave us an inquiry ticket on https://kashier.io for questions.


