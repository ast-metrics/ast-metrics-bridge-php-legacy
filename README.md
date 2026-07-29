# halleck45/ast-metrics

This package was renamed to [`ast-metrics/ast-metrics`](https://packagist.org/packages/ast-metrics/ast-metrics).

```bash
composer remove halleck45/ast-metrics
composer require --dev ast-metrics/ast-metrics
```

The command stays the same: `php vendor/bin/ast-metrics analyze src`.

This repository only exists to keep the old Composer name resolvable, so that an existing
`composer.json` or `composer.lock` keeps working. The code lives at
[ast-metrics/ast-metrics-bridge-php](https://github.com/ast-metrics/ast-metrics-bridge-php).
