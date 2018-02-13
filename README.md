# OSF encryption, decryption and hashing component

A component that simplifies the management of cryptographic operations.

## Installation

You need at least php 7.1 and `composer`:

```bash
sudo apt install composer
```

### In your application via composer

This is the recommended way to use this feature in a non-osf project.

Just add `osflab/crypt` in your composer.json file.

### From github

To test the component or participate in its development.

```bash
git clone https://github.com/osflab/crypt.git
cd crypt && composer update
```

Unit tests launch:

```bash
php ./vendor/osflab/test/run-tests.php
```
