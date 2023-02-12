# ⚡️Kirby Speed Benchmark

Benchmarking multiple configurations settings with the latest php version and the latest kirby release. Every Configuration test is based upon a clean php.ini-production
copy provided with the latest php installment.

## Current Versions (12 February 2023)

- Php : 8.2.2 (Thread safe)
- Kirby : 3.9.1
- Starterkit : 3.9.1

## PHP settings for kirby 

These PHP extensions are required by Kirby.

- mbstring extension
- curl extension
- ctype extension (deprecated > PHP 8.1)
- gd extension

Source: https://getkirby.com/docs/guide/quickstart

## Configurations tested:

- base (production.ini + Kirby PHP extensions)
- base + Opcache

## Benchmark tool:

[fasthttploader](https://github.com/GeorgeLuo/fasthttploader)

```
powershell > fasthttploader http://localhost:8000
```
!Running 100 connections in 10 seconds http://localhost:8000


## Check PHP

add phpinfo(); to the index.php (Kirby - Starterkit)
