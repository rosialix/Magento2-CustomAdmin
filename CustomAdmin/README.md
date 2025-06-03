# Magento 2 Module Add a custom button in admin grid

#### Purpose of the module:
This module allows you to create a new column containing an action button in the customer admin grid.
#### Need Magento 2 development help:
Please feel free to contact me, if you need Magento 2 development help.
* Email - rosialix@gamil.com
  
#### Installation of module:

> [!NOTE]
> I installed and tested this module for Magento 2.4.7-p1.

  1. Please take a pull of this repository and add module code in the "app/code/Ross/CustomAdmin" folder.
  2. Run below commands <br>

```
php bin/magento cache:flush 
php bin/magento setup:upgrade 
php bin/magento setup:di:compile 
php bin/magento setup:static-content:deploy -f
```
    
#### Testing of module:
Go to Admin Customer -> All Customer
![image](https://github.com/user-attachments/assets/7393651e-2560-4be8-a41f-8d837777c2e4)

![image](https://github.com/user-attachments/assets/110de775-45c1-4363-a503-490bb0e520b0)

#### Thank You
