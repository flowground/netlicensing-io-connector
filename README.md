# ![LOGO](logo.png) Labs64 NetLicensing RESTful API Test Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Labs64 NetLicensing RESTful API Test Center API (version 2.x).

Generated from: https://api.apis.guru/v2/specs/netlicensing.io/2.x/swagger.json<br/>
Generated at: 2019-05-07T17:43:13+03:00

## API Description

The Labs64 <a href='https://www.labs64.de/confluence/x/pwCo' target='_blank'>NetLicensing RESTful API</a> gives you access to NetLicensing’s core features.<br/><br/><strong>Authentication</strong><br/>You authenticate to the NetLicensing API by providing your account credentials or simply use our demo account - <code>demo:demo</code><br/><br/>Find out more about Labs64 NetLicensing at <a href='https://netlicensing.io' target='_blank'>netlicensing.io</a>

## Authorization

Supported authorization schemes:
- API Key- Basic Authentication

## Actions

### Licenses list

> Return a list of all licenses for the current vendor

*Tags:* `License`

### Create license

> Creates a new license

*Tags:* `License`

### Delete license

> Delete license by a licenseNumber

*Tags:* `License`

#### Input Parameters
* `licenseNumber` - _required_ - Unique number (across all products/licensees of a vendor) that identifies the license. Vendor can assign this number when creating a license or let NetLicensing generate one. Read-only after corresponding creation transaction status is set to closed.

### Get license

> Get license by a licenseNumber

*Tags:* `License`

#### Input Parameters
* `licenseNumber` - _required_ - Unique number (across all products/licensees of a vendor) that identifies the license. Vendor can assign this number when creating a license or let NetLicensing generate one. Read-only after corresponding creation transaction status is set to closed.

### Update license

> Update license by a licenseNumber

*Tags:* `License`

#### Input Parameters
* `licenseNumber` - _required_ - Unique number (across all products/licensees of a vendor) that identifies the license. Vendor can assign this number when creating a license or let NetLicensing generate one. Read-only after corresponding creation transaction status is set to closed.

### Licensees list

> Return a list of all licensees for the current vendor

*Tags:* `Licensee`

### Create licensee

> Creates a new licensee

*Tags:* `Licensee`

### Delete licensee

> Delete a licensee by number

*Tags:* `Licensee`

#### Input Parameters
* `licenseeNumber` - _required_ - Unique number (across all products of a vendor) that identifies the licensee.
* `forceCascade` - _optional_ - Force object deletion and all descendants.

### Get licensee

> Return a licensee by licenseeNumber

*Tags:* `Licensee`

#### Input Parameters
* `licenseeNumber` - _required_ - Unique number (across all products of a vendor) that identifies the licensee. Vendor can assign this number when creating a licensee or let NetLicensing generate one. Read-only after creation of the first license for the licensee.

### Update licensee

> Sets the provided properties to a licensee. Return an updated licensee

*Tags:* `Licensee`

#### Input Parameters
* `licenseeNumber` - _required_ - Unique number (across all products of a vendor) that identifies the licensee. Vendor can assign this number when creating a licensee or let NetLicensing generate one. Read-only after creation of the first license for the licensee.

### Transfer licenses

> Licenses transfer between licensees

*Tags:* `Licensee`

#### Input Parameters
* `licenseeNumber` - _required_ - Licensee number with a maximum length of 1000 characters

### Validate licensee

> Validates active licenses of the licensee

*Tags:* `Licensee`

#### Input Parameters
* `licenseeNumber` - _required_ - Licensee number with a maximum length of 1000 characters

### License Templates list

> Return a list of all license templates for the current vendor

*Tags:* `License Template`

### Create license template

> Creates a new license template

*Tags:* `License Template`

### Delete license template

> Delete a license template by number.

*Tags:* `License Template`

#### Input Parameters
* `licenseTemplateNumber` - _required_ - Unique number (across all products of a vendor) that identifies the license template.
* `forceCascade` - _optional_ - Force object deletion and all descendants.

### Get license template

> Return a license template by licenseTemplateNumber

*Tags:* `License Template`

#### Input Parameters
* `licenseTemplateNumber` - _required_ - Unique number (across all products of a vendor) that identifies the license template. Vendor can assign this number when creating a license template or let NetLicensing generate one. Read-only after creation of the first license from this license template.

### Update license template

> Sets the provided properties to a license template. Return an updated license template

*Tags:* `License Template`

#### Input Parameters
* `licenseTemplateNumber` - _required_ - Unique number (across all products of a vendor) that identifies the license template. Vendor can assign this number when creating a license template or let NetLicensing generate one. Read-only after creation of the first license from this license template.

### Payment Methods list

> Return a list of all payment methods for the current vendor

*Tags:* `Payment Method`

### Get payment method

> Return a payment method info by paymentMethodNumber

*Tags:* `Payment Method`

#### Input Parameters
* `paymentMethodNumber` - _required_ - Payment method number

### Update payment method

> Sets the provided properties to a payment method. Return an updated payment method

*Tags:* `Payment Method`

#### Input Parameters
* `paymentMethodNumber` - _required_ - Payment method number

### Products list

> Return a list of all configured products for the current vendor

*Tags:* `Product`

### Create product

> Creates a new product

*Tags:* `Product`

### Delete product

> Delete a product by number

*Tags:* `Product`

#### Input Parameters
* `productNumber` - _required_ - Unique number that identifies the product.
* `forceCascade` - _optional_ - Force object deletion and all descendants.

### Get product

> Return a product by productNumber

*Tags:* `Product`

#### Input Parameters
* `productNumber` - _required_ - Unique number that identifies the product.

### Update product

> Sets the provided properties to a product. Return an updated product

*Tags:* `Product`

#### Input Parameters
* `productNumber` - _required_ - Unique number that identifies the product.

### Product Modules list

> Return a list of all product modules for the current vendor

*Tags:* `Product Module`

### Create product module

> Creates a new product module

*Tags:* `Product Module`

### Delete product module

> Delete a product module by number

*Tags:* `Product Module`

#### Input Parameters
* `productModuleNumber` - _required_ - Unique number (across all products of a vendor) that identifies the product module.
* `forceCascade` - _optional_ - Force object deletion and all descendants.

### Get product module

> Return a product module by productModuleNumber

*Tags:* `Product Module`

#### Input Parameters
* `productModuleNumber` - _required_ - Unique number (across all products of a vendor) that identifies the product module. Vendor can assign this number when creating a product module or let NetLicensing generate one. Read-only after creation of the first licensee for the product.

### Update product module

> Sets the provided properties to a product module. Return an updated product module

*Tags:* `Product Module`

#### Input Parameters
* `productModuleNumber` - _required_ - Unique number (across all products of a vendor) that identifies the product module. Vendor can assign this number when creating a product module or let NetLicensing generate one. Read-only after creation of the first licensee for the product.

### Tokens list

> Return a list of all tokens for the current vendor

*Tags:* `Token`

### Create token

> Create token by tokenType and additional token parameters

*Tags:* `Token`

### Delete token

> Delete a token by number

*Tags:* `Token`

#### Input Parameters
* `tokenNumber` - _required_ - Token number

### Get token

> Return a token by tokenNumber

*Tags:* `Token`

#### Input Parameters
* `tokenNumber` - _required_ - Token number

### Transactions list

> Return a list of all transactions for the current vendor

*Tags:* `Transaction`

### Create transaction

> Creates a new transaction

*Tags:* `Transaction`

### Get transaction

> Return a transaction by transactionNumber

*Tags:* `Transaction`

#### Input Parameters
* `transactionNumber` - _required_ - Unique number (across all products of a vendor) that identifies the transaction

### Update transaction

> Sets the provided properties to a transaction. Return an updated transaction

*Tags:* `Transaction`

#### Input Parameters
* `transactionNumber` - _required_ - Unique number (across all products of a vendor) that identifies the transaction

### License Types list

> Return a list of all license types supported by the service

*Tags:* `Utility`

### Licensing Models list

> Return a list of all licensing models supported by the service

*Tags:* `Utility`

## License

**flow**ground :- Telekom iPaaS / netlicensing-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
