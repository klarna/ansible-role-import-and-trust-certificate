# Ansible Role - Import & Trust PEM certificate [![Build Status](https://travis-ci.org/klarna/ansible-role-import-and-trust-certificate.svg?branch=master)](https://travis-ci.org/klarna/ansible-role-import-and-trust-certificate)

Ansible role to import PEM certificates so that they are always trusted on OSX. Part of Klarna's setup when using Superlumic.

## Requirements

* OSX 10.10+

## Role variables

For the role to work you must set a variable depicting the URL where the
certificate can be obtained. See below.

```yaml
certificate_url: http://placewithcerts.com/certificate.pem
```

Additionally, you may set a variable depicting whether or not SSL certificates
are to be validated (defaults to "yes"):

```yaml
validate_ssl: no
```

# Usage

Just use this as you would any Ansible role.

# License

Apache 2.0

# Author

Guy Rozen
