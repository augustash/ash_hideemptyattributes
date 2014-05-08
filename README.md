Title:  Ash_HideEmptyAttributes Extension  
Author: Josh Johnson  
Email:  core@augustash.com  
Date:   May 08, 2014  

# Description

Skip listing of attributes if they have a blank/empty value for the attribute. Typically these are displayed as a "N/A" or "No" value within the product's additional info table.

# Features

+ Extends `Mage_Catalog_Helper_Output` to add methods for determining if the "value" is indeed a valid option for the attribute
+ Checks the "value" against attribute options for product attributes with frontend input of select or multiselect
+ Overrides the `frontend/base/default/template/catalog/product/view/attributes.phtml` file to wrap displaying of table rows with a helper method from `Ash_HideEmptyAttributes_Helper_Output`.

# Dependencies

+ Ash_Core
+ Mage_Catalog

------------

# Installation


### Manual Installation

1. Clone module with [modman](https://github.com/colinmollenhour/modman)
2. Delete all contents of the Magento cache

### Ash_Up Installation

**Assumes you have the `Ash_Up` module installed already. [View on Github](https://github.com/augustash/ash_up)**

From within your Magento project's directory

```bash
$ php -f shell/up.php -- --install ash_core,ash_hideemptyattributes
```

```
@copyright  Copyright (c) 2014 August Ash, Inc. (http://www.augustash.com)
```
