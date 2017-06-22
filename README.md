ICanBoogie's inflector is one of the few multi-lingual inflectors available in the PHP ecosystem.  It supports a number of common languages and provides methods for transforming text in multiple ways including:

- Pluralization
- Singularization
- Camel Casing
- Underscoring

## Installation

```
composer require hiraeth/icb-inflector
```

The `icb-inflector.jin` configuration will be automatically copied to your `config` directory via [opus](https://github.com/imarc/opus).

## Delegates

| Operative Class          | Operative Intefaces  | Provides
|--------------------------|----------------------|------------------------------------------------------
| `ICanBoogie\Inflector`   | Class Only           | Configuration for the locale

## Providers

No providers are included in this package.

## Configuration

```ini
; The locale to use for inflection (en, fr, ...)

locale = en
```

## Usage

See [the ICanBoogie Inflector documentation](https://github.com/ICanBoogie/Inflector) for more information on what types of inflection are available.
