# ⚡️Kirby Speed Benchmark

Benchmarking multiple configurations settings with the latest php version and the latest kirby release. Every Configuration test is based upon a clean production.ini copy provided with the latest php installment.

## Current Versions (12 February 2023)

- Php : 8.2.2 (Thread safe)
- Kirby : 3.9.1
- Starterkit : 3.9.1

## PHP settings for kirby 

These PHP extensions are required by Kirby.

- mbstring extension
- curl extension
- ctype extension
- gd extension

Source: https://getkirby.com/docs/guide/quickstart

## Current configurations tested:

- base (production.ini + Kirby PHP extensions)
- base + Opcache

## Benchmark tool:

Auto Cannon
