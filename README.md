![Plott Core WP Installer](docs/header.png)

A Composer plugin for installing WordPress core into a custom directory. Drop-in replacement for `johnpbloch/wordpress-core-installer`.

## Installation

```bash
composer require plott/plottcore-wp-installer
```

## Usage

Add the install directory to your project's `composer.json`:

```json
{
  "extra": {
    "wordpress-install-dir": "public/wp"
  }
}
```

Then require a WordPress core package (e.g. `roots/wordpress` or `johnpbloch/wordpress`).

## Requirements

- PHP >= 5.6
- Composer 1.x or 2.x

## License

GPL-2.0-or-later
