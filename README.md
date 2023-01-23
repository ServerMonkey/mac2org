# mac2org
Convert a MAC address to the name and address of the organization.
Search IEEE databse for MAC adresses based on an organizations name.
Also shows QEMU and XEN MACs.

Tested on Debian 11

### How to use
mac2org <MAC_ADRESS>

org2mac <ORG_SEARCH_STRING>

### Example usage
mac2org 00:16:3e:97:76:a5
mac2org 00-16-3E

org2mac Apple
org2mac "intel corp"
