# Hyvä Order Success Page

**Hyvä Order Success Page is a part of MageINIC Order Success Page extension that adds Hyvä features.** This extension extends Order Success Page definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-order-success-page

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Order Success Page requires installing [MageINIC Order Success Page](https://github.com/mageinic/order-success-page) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/order-success-page
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
