# Redpa2ya Base for Magento 2

## How to install & upgrade Redpa2ya_Base

### 1. Install via composer (recommend)

Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require redpa2ya/magento2-module-base
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update redpa2ya/magento2-module-base
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and paste

If you don't want to install via composer, you can use this way. 

- Download [the latest version here](https://github.com/redpa2ya/magento2-module-base/archive/master.zip) 
- Extract `master.zip` file to `app/code/Redpa2ya/Base` (Make sure you created the folder `app/code/Redpa2ya/Base` if it doesn't exist).
- Go to Magento root folder and run upgrade command line to install `Redpa2ya_Base`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
