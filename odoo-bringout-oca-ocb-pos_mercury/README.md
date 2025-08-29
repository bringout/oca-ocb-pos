# Vantiv Payment Services


Allow credit card POS payments
==============================

This module allows customers to pay for their orders with credit
cards. The transactions are processed by Vantiv (developed by Wells
Fargo Bank). A Vantiv merchant account is necessary. It allows the
following:

* Fast payment by just swiping a credit card while on the payment screen
* Combining of cash payments and credit card payments
* Cashback
* Supported cards: Visa, MasterCard, American Express, Discover
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-pos_mercury
```

## Dependencies

This addon depends on:
- web
- barcodes
- point_of_sale

## Manifest Information

- **Name**: Vantiv Payment Services
- **Version**: 1.0
- **Category**: Sales/Point of Sale
- **License**: LGPL-3
- **Installable**: True

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `pos_mercury`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Reports: doc/REPORTS.md
- Security: doc/SECURITY.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md
