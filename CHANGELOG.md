## 1.0.4 (Unreleased)
## 1.0.3 (January 29, 2019)

IMPROVEMENTS:

* **Password hashing:** Provider will no longer store passwords in state files as plaintext

DOCUMENTATION UPDATES:

* Updated "Skip SSL Verify" documentation to match actual implementation

## 1.0.2 (September 05, 2018)

IMPROVEMENTS:

* **Provider Configuration:** Added support for skip TLS check on provider init ([#12](https://github.com/terraform-providers/terraform-provider-influxdb/issues/11))

## 1.0.1 (July 19, 2018)

Bug Fixes:

* Unapplied list of grants changes detected based on ordering ([#6](https://github.com/terraform-providers/terraform-provider-influxdb/issues/6))

## 1.0.0 (February 09, 2018)

IMPROVEMENTS:

* **resource_database:** Added support for retention policy configuration ([#3](https://github.com/terraform-providers/terraform-provider-influxdb/issues/3))

## 0.1.0 (June 20, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
