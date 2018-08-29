# Мой стандарт для phpcs

## Установка

```bash
composer global require vite4eg/phpcs.code_style
```

## Глобальная регистрация стандарта

```bash
phpcs --config-set installed_paths "$(composer config home -g)"/vendor/standards/php-code-style
```