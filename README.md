# Octo
## Laravel Payment Octo

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://teamprodev.uz)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/teamprodev/laravel_payment_octo)

Teamprodev Laravel Payment Octo is  payment ready configurable composer package for laravel.

- Less effort
- Extendable
- Configurable
- ✨Magic ✨

## Features

- Visa and Mastercard payment method
- Notify user about payment
- Secure Payment
- Extend Payment Service

Laravel Payment Payme package made easy your development process for Mastercard and Visa payment methods.
Find more information about integration in [Octo](https://help.octo.uz/ru/s-chego-nachat)


## Installation

Payme requires [Laravel](https://laravel.com/) v7+ to run.

Install package using composer.

```sh
composer require teamprodev/laravel_payment_payme
```

Publish Service Provider

```sh
php artisan vendor:publish --provider="Teamprodev\Providers\OctoServiceProvider" --tag="config"
```

Migrate Transaction and orders table

```sh
php artisan migrate
```
ADD variable to .env

OCTO_TEST=false
OCTO_SHOP_ID=
OCTO_SECRET=
OCTO_TRANSACTIONS_TABLE=octo_transactions
OCTO_ORDERS_TABLE=orders
OCTO_USERS_TABLE=users
OCTO_REDIRECT_AFTER_VERIFY=
OCTO_REDIRECT_URL=
OCTO_NOTIFY_URL=


## License

MIT

MIT License

Copyright (c) 2022 Asadbek Fayzulloev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

