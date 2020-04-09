# Verifa Helm Charts

This repository is intended to collect some useful Helm charts that the verifa team have put together, in the hope that they can be useful for anyone else!

note: **work in progress**

## stunnel-google-ldap

Verifa use Google Suite for our business and Google provide an LDAP service. As most tools under the sun provide LDAP authentication support we decided to somewhat standardise on LDAP for authentication.

However, Google LDAP requires authentication via username/password (very standard) but also through a certificate and private key pair, which is less usual and often not supported. What did we do? Created this chart!

