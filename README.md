## PlacetoPay Magento 2 Spanish (Chile) Language Pack

[PlacetoPay][link-placetopay] Package to support Chilean language on [Magento 2][link-magento] Stable

## Overview

1. Install Spanish (Chile) Language Pack
2. How to active Spanish (Chile) language pack
3. Supported Magento versions

## 1. How to Install Spanish Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Spanish language pack via composer is never easier.

**Install Spanish (Chile) pack**:

```
composer require placetopay/magento2-spanish-chile-language-pack
php bin/magento setup:static-content:deploy es_CL
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update Spanish (Chile) pack**:

```
composer update placetopay/magento2-spanish-chile-language-pack
php bin/magento setup:static-content:deploy es_ES
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Spanish (Chile) language pack
- Step 2: Unzip Spanish (Chile) pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Spanish language pack

You can download the language pack from above link

#### Step 2: Unzip Spanish pack

Unzip the Spanish language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/PlacetoPay/
```

Rename folder `magento-2-spanish-chile-language-pack` to `es_cl`.

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

```
php bin/magento cache:clean
php bin/magento cache:flush
```

### ✓ Method #3. Download and install manually (Not recommended)

To download and install Spanish (Chile) pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/sgodoy17/magento-2-spanish-chile-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/sgodoy17/magento-2-spanish-chile-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/PlacetoPay/es_cl/`

This language pack code is: **es_cl**

#### Step 2: Flush cache

```
php bin/magento cache:clean
php bin/magento cache:flush
```

## 2. How to Activate the Spanish (Chile) language pack

Now time to activate the Spanish (Chile) language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
and select Spanish (Chile) from the list.

## 3. Supported Magento versions

It supports all Magento 2 versions include Magento 2 open-source (Community), Magento 2 Commerce (EE), Magento Cloud, Magento B2B, Magento MSI.

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x

[link-placetopay]: https://www.placetopay.com
[link-magento]: https://magento.com



