# [Keyup](http://www.keyup.eu/) Mass Shipment Extension for Magento

Mass Shipment is a simple extension for Magento that provides a mass action
for shipping orders. This is not provided in Magento by default because specific
parameters like package tracking number have to be set differently for each
shipment. However there are edge cases where this is not necessary, and this
extensions aims to help in these cases.

## Usage

The extension has no configuration options and only provides two new mass
actions in the Orders grid (Sales -> Orders). Those are:

* _Ship (no emails)_ – creates a shipment (containing all shippable order items)
  for every selected order
* _Ship (with emails)_ – creates shipments the same way _and_ sends shipment
  notification emails to customers

## Compatibility

This extension was tested with Magento CE 1.9, but no really version-specific
code is used, so it should work with both newer and older (at least back till
1.7) Magento versions, and most possibly it will work with Magento Enterprise
too.

## License

The code is licensed under the MIT license. We'll appreciate if you
[let us know](http://www.keyup.eu/en/contact) that (and how) you use this
extension.