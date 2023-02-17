# Magento 2 International Telephone Validation with Country flag

![Main Image | Thumbnail | Magento 2](https://github.com/nathaodedara/magento2-international-telephone-validation/blob/main/screenshots/how-to-add-international-telephone-validation-with-country-flag-magento-2.jpg?raw=true)

## Main Functionalities
A Magento 2 extension to support international of telephone validation for all countries and also add country flag to the telephone field. Automatically detect user's country and set as selected

- Add functionality to allow user to select their country for telephone input
- Automatically validates the given telephone number based on the selected country
- Gives nice and easy look for the users
- Site owner can also use backend configurations options to tweak or change the settings of the telephone input such as if they want to display country code (ex. +91) or not.
- It can also detect a users country based on their IP address and sets it by default automatically.

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
