# rclone

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/rclone) [![Build Status](https://img.shields.io/drone/build/rolehippie/rclone/master?logo=drone)](https://cloud.drone.io/rolehippie/rclone) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/rclone)](https://github.com/rolehippie/rclone/blob/master/LICENSE) 

Ansible role to install and configure rclone backup solution. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [rclone_definitions](#rclone_definitions)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### rclone_definitions

List of remote definitions

#### Default value

```YAML
rclone_definitions: []
```

#### Example usage

```YAML
rclone_definitions:
  - name: flexvault
    endpoint: https://s3.tms.proactcloud.de
    access_key: 8OK3V7PXMFDUTJJ7O4MT
    secret_key: aCP5DMfw1-usOPkcu+wHSaRkgbAHY5O4rOKPCK6+
    bucket: backups
    filename_ecryption: standard
    directory_encryption: True
    primary_password: Mire5vohR0ohn6bei8tahngair4oophae6IefochuquopheemoaH
    secondary_password: iechaa6xoxa9rie1iu0ucoM9Fa2da8thao1hai9Iv8wohphievie
```

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
