Atournayre Fixtures
================

This library helps creating fixtures (with Alice).

Installation
------------

Use [Composer] to install the package:

```bash
composer require atournayre/fixtures --dev
```

Features
----------
* Uuid generator for Alice
* Hash password for Alice

Example
----------
```yaml
App\Entity\User:
  admin:
    # id: '<uuidV1()>'
    id: '<uuidV4()>'
    # id: '<uuidV6()>'
    # id: '<uuidV7()>'
    # id: '<uuidV8(uuid)>'
    email: 'admin@example.com'
    password: '<hashPassword(super_password)>'
```

Contribute
----------

Contributions to the package are always welcome!

* Report any bugs or issues you find on the [issue tracker].
* You can grab the source code at the package's [Git repository].

License
-------

All contents of this package are licensed under the [MIT license].

[Composer]: https://getcomposer.org

[The Community Contributors]: https://github.com/atournayre/fixtures/graphs/contributors

[issue tracker]: https://github.com/atournayre/fixtures/issues

[Git repository]: https://github.com/atournayre/fixtures

[MIT license]: LICENSE
