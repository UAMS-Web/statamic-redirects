# Redirects

A Statamic add-on for redirect rules: a `redirects` global set answered on the site's 404 path, rules served on redirect domains, an edge redirect manifest built from those rules, and a Control Panel workflow for requesting and approving marketing redirects.

The code is being moved into this add-on from `UAMS-Web/uams-statamic`; until that lands, this package installs and registers but serves nothing. The work is tracked in [UAMS-Web/uams-statamic#397](https://github.com/UAMS-Web/uams-statamic/issues/397).

## Requirements

PHP 8.4 or later and Statamic 6.35 or later.

## Installation

```bash
composer require uams-web/statamic-redirects
```

Statamic discovers the add-on through Composer. To change its settings, publish the config file:

```bash
php artisan vendor:publish --tag=statamic-redirects-config
```

## License

MIT. See [`LICENSE`](LICENSE).

## Documentation

- [`docs/DEVELOPMENT.md`](docs/DEVELOPMENT.md): developing the add-on against a host.
- [`docs/SUBMISSION.md`](docs/SUBMISSION.md): the Packagist and Marketplace checklist.
- [`docs/DECISIONS.md`](docs/DECISIONS.md): the decision log.
