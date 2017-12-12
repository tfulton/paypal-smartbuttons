paypal-smartbuttons
-------------------
A project to exercise and test one's understanding of PayPal Smart Buttons.

# Overview
The purpose of this project is to implement numerous variations of Smart Buttons.  By going through this exersize, we familiarize ourselves with both the configurations overall.

# Requirements
Implement individual checkout experiences using various Smart Button configurations.  Including:
* Horizontal Orientation
* Vertical Orientation
* Various PayPal Buttons Types (Checkout, Pay, Buy Now, PayPal button)
* Various [FUNDING types](https://github.com/paypal/paypal-checkout/blob/master/src/config/constants.js#L122)
* Credit (w/second button)
* Multi-Currency and Multi-Language Combinations (see [supported currency](https://developer.paypal.com/docs/integration/direct/rest/currency-codes/) and [locale codes](https://developer.paypal.com/docs/classic/api/locale_codes/))

**HINT:** not all combinations will together. For instance, vertical orientation allows some funding sources, while horizontal does not.  Some countries allow some funding sources, while others do not.  *This is part of the challenge!*

# Implementation
* Put your REST App 'clientId' in the appropriate location of [template.html](./template.html)
* Download a copy or clone of this project to use as your base of work.
* Copy [template.html](./template.html) for each of your examples that you would like to preserve.

# Test and Validation
* Page must render.
* Funds are deposited in the target sandbox merchant account as required by the currency and funding type.

