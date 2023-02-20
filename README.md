## <ins>This extension is no longer available for FREE, you can purchase it from Magento Marketplace [CLICK HERE](https://marketplace.magento.com/ananta-module-telephonevalidation.html "International Telephone Validation with Country flag For Magento 2 - Magento Marketplace").

# International Telephone Validation with Country flag For Magento 2

![Main Image | Thumbnail | Magento 2](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/how-to-add-international-telephone-validation-with-country-flag-magento-2.jpg?raw=true)

## Main Functionalities
A Magento 2 extension to support international telephone validation for all countries and also add a country flag to the telephone field. Automatically detect the user's country and set it as selected

- Add functionality to allow a user to select their country for telephone input
- This extension adds international validation for all country-wise lists with flags on all telephone fields available in Magento, Customer Address Forms, Checkout Address Forms and on Contact Us Page as well.
- Automatically validates the given telephone number based on the selected country
- Gives a nice and easy look for the users
- Site owners can also use backend configuration options to tweak or change the settings of the telephone input such as if they want to display country code (ex. +91) or not.
- It can also detect a user's country based on their IP address and sets it by default automatically.

## Installation
\* = in production please use the `--keep-generated` option

 - Unzip the zip file in `app/code/Ananta`
 - Enable the module by running `php bin/magento module:enable Ananta_TelephoneValidation`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`
 - Now you can see the telephone input with country flag on the frontend

## Configuration
 - Once installation is done, you can go to **Admin panel**. Go to **Stores > Configuration > Ananta Systems > Telephone Validation**, and set the given options for modifications as per your requirements or you can keep it as it is by the default as well.
 ![Configuration Setting](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-configuration.png?raw=true)

## Screenshots

![Screenshots](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-checkout-billing-address-new.png?raw=true)
![Screenshots](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-checkout-shipping-address.png?raw=true)
![Screenshots](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-checkout-shipping-address-new.png?raw=true)
![Screenshots](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-contact-us-page.png?raw=true)
![Screenshots](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-customer-new-address.png?raw=true)
![Screenshots Configuration](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/magento-2-international-telephone-validation-with-country-flags-full-configurations.png?raw=true)
