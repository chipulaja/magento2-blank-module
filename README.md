# Blank module

the purpose of this code is to demonstrating how to create a blank module on magento 2.

to create blank module on magento 2 you need files :

- registration.php
- etc/module.xml

## how to install this module

There are two ways to install this module

### first

copy and paste this code into `app/code/Chipulaja/BlankModule`
`php bin/magento module:enable Chipulaja_Magento_BlankModule`

### second

```bash
composer requires chipulaja\magento2-blank-module
php bin/magento module:enable Chipulaja_Magento_BlankModule
```
