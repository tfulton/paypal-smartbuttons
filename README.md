paypal-smartbuttons
-------------------
A project to exercise and test one's understanding of PayPal Smart Buttons.

# Overview
The purpose of this project is to implement numerous variations of Smart Buttons.  By going through this exersize, we familiarize ourselves with both the configurations overall.

# Requirements
Implement individual checkout experiences using various Smart Button configurations.  Including:
* Horizontal Orientation
* Vertical Orientation
* Various [FUNDING types](https://github.com/paypal/paypal-checkout/blob/master/src/config/constants.js#L122)
* Various PayPal Button Types (Checkout, Pay, Buy Now, PayPal button)
* Credit w/second button
* Multi-Currency and Multi-Language Combinations (see [supported currency](https://developer.paypal.com/docs/integration/direct/rest/currency-codes/) and [locale codes](https://developer.paypal.com/docs/classic/api/locale_codes/))
* Combinations of the Above - depending on your appetite for experimentation.

**HINT:** not all combinations work together. For instance, the FUNDING.ELV type works only with Germany (DE) and Austria (AT), FUNDING.CREDIT works with US, GB and DE.  Use these combinations to test your understanding of the options available.  *This is part of the challenge!*

# Implementation
* Put your REST App 'clientId' in the appropriate location of [template.html (line 88)](./template.html)
* Download a copy or clone this project to use as your base of work.
* Copy [template.html](./template.html) for each of your examples that you would like to preserve.
* Import [pp_rest_postman_collection.json](./pp_rest_postman_collection.json) into Postman for auth, capture, void, etc.

# Test and Validation
* Page must render.
* Complete payment flow.  The included example completes the "execute" portion of the payment cycle.
* Utilize the Postman collection included (or any PayPal REST collection used thus far) to complete payment life cycle events as desired.
* Funds are deposited in the target sandbox merchant account as required by the currency and funding type.

# Extra Credit
Try any of the following client side implementations depending on your interest:
* [Mark](https://developer.paypal.com/demo/checkout/#/pattern/mark)
* [Confirmation Page](https://developer.paypal.com/demo/checkout/#/pattern/confirm)
* [INSTRUMENT_DECLINED Redirect](https://developer.paypal.com/docs/integration/direct/express-checkout/integration-jsv4/customize-the-checkout-flow/#redirect-for-an-alternate-funding-source)

