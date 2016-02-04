# Description

Skip listing of attributes if they have a blank/empty value for the attribute. Typically these are displayed as a "N/A" or "No" value within the product's additional info table.

## Features

+ Extends `Mage_Catalog_Helper_Output` to add methods for determining if the "value" is indeed a valid option for the attribute
+ Checks the "value" against attribute options for product attributes with frontend input of select or multiselect
+ Overrides the `frontend/base/default/template/catalog/product/view/attributes.phtml` file to wrap displaying of table rows with a helper method from `Ash_HideEmptyAttributes_Helper_Output`.

------------

## Installation

* Install the extension via [Composer](https://getcomposer.org/)
* Install the extension via [modman](https://github.com/colinmollenhour/modman)
* You can also [download from Github](https://github.com/augustash/ash_hideemptyattributes/archive/master.zip) and unzip the archive in your project root

## Dependencies

* [Ash_Core](https://github.com/augustash/ash_core)

-----

```
@copyright  Copyright (c) 2016 August Ash, Inc. (http://www.augustash.com)
```
