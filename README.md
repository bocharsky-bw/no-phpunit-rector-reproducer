Symfony Demo Application
========================

The "Symfony Demo Application" where was dropped PHPUnit Composer dependency and all PHPUnit tests.

To reproduce the error, clone this repo, install dependencies, and run:

```bash
./vendor/bin/rector process src
```

It will show:

> Class PHPUnit\Framework\TestCase not found.
