## Magento 2 Ukrainian Language Pack

Maybe **Magento 2 Ukrainian Language Pack** should be the first must-have thing to discover if you have an eCommerce store in Ukraine. Is it really important? The answer is absolutely yes for me. Because when you start a business in a new country, ensure that the different in the language culture is the biggest barrier. The deals are not be successful if the buyers cannot understand what you are mentioning on the website. Today, I'm going to introduce the Ukrainian Language Package so that you can use Ukrainian as a native language for stores in Ukraine. You have to download a zip translation file via the link and install it on the store. Then, you should choose the right store locale (Ukrainian (Ukraine)) from the backend. Please get the guides below for the perfect convertion.

Read more [Magento 2 Ukrainian Language Pack](https://www.mageplaza.com/magento-2-ukrainian-language-pack.html)

![Mageplaza Ukrainian language pack](https://i.imgur.com/qjWPj1W.png)

## Overview

1. Language Package Process
2. Install Ukrainian Language Pack
3. How to active Ukrainian language pack
4. How to contribute
5. Supported Magento versions
6. Notes
7. Language package authors

## 1. Language Package Process

This is status of Ukrainian Language Pack, you can see how many percentage of this project has been done.

![language pack](http://progressed.io/bar/{{process}}?title=translated)

It is not fully translated? Feel free to contribute:
- [On Crowdin]({{crowdin}}): It takes time to approve your contribution by Magento team.
- [On Github]({{github_url}}/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Ukrainian Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Ukrainian language pack via composer is never easier.

**Install Ukrainian pack**:

```
{{composer_install}}
```


**Update  Ukrainian pack**:

```
{{composer_update}}
```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)

Or use these keys:

```
Public Key: c7af1bfc9352e9c986637eec85ed53af
Private Key: 17e1b72ea5f0b23e9dbfb1f68dc12b53
```



### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Ukrainian language pack
- Step 2: Unzip Ukrainian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Ukrainian language pack

You can download the language pack from above link

#### Step 2: Unzip Ukrainian pack

Unzip the Ukrainian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/Mageplaza/
```

Rename folder `{{github_repo_name}}` to `{{magento_package_code}}`.


You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Ukrainian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip]({{github_latest_version}})
- [Download .tar.gz]({{github_latest_version_tar}})

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/Mageplaza/{{magento_package_code}}/`

See this screenshot:

![Ukrainian pack](https://cdn3.mageplaza.com/media/general/language-pack.png)

This language pack code is: **{{magento_package_code}}**

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to Active the Ukrainian language pack 

Now time to active the Ukrainian language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Ukrainian language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

Contribute to this language at :
- [On Crowdin]({{crowdin}}): It takes time to approve your contribution by Magento team.
- [On Github]({{github_url}}/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 open-source](https://www.mageplaza.com/download-magento/) (Community), Magento 2 Commerce (EE), Magento Cloud, Magento B2B, Magento MSI.

{{magento_versions}}


## 6. Notes 

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue]({{github_url}}/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2]({{crowdin}})
- Magento Community
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References 

- https://www.mageplaza.com/magento-2-ukrainian-language-pack.html
- https://crowdin.com/project/magento-2



## Mageplaza extensions on Magento Marketplace, Github


- [Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [One Step Checkout](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)
- [SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html) ; [SMTP on Github](https://github.com/mageplaza/magento-2-smtp)
- [Blog](https://github.com/mageplaza/magento-2-blog)
- [Security](https://marketplace.magento.com/mageplaza-module-security.html)
- [Social Login](https://github.com/mageplaza/magento-2-social-login)
- [SEO](https://github.com/mageplaza/magento-2-seo) ; [SEO on Marketplace](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)
- [SMTP](https://github.com/mageplaza/magento-2-smtp)
- [Product Slider](https://github.com/mageplaza/magento-2-product-slider)
- [Banner](https://github.com/mageplaza/magento-2-banner-slider)
- [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



