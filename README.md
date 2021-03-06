# Hue Nini light - Gradually turns off the lights

[![Code Climate](https://codeclimate.com/github/PurpleBooth/hue-nini-light/badges/gpa.svg)][codeclimate]
[![Docker Repository on Quay](https://quay.io/repository/purplebooth/hue-nini-php/status "Docker Repository on Quay")][quay]

This is a bit of a toy I use to turn of my lights slowly in my house. Staggers them a bit so they don't all flick off at
once.

It's written in PHP.

## Usage

```
$ php nini.php
nini.php minuites-to-lights-out hue-ip hue-password
```

## Setup

```
php -r "readfile('https://getcomposer.org/installer');" | php
php composer.phar install
```

Phue has [a guide on how to create a hue password][guide]

[quay]: https://quay.io/repository/purplebooth/hue-nini-php
[codeclimate]: https://codeclimate.com/github/PurpleBooth/hue-nini-light
[guide]: https://github.com/sqmk/Phue#issuing-commands-testing-connection-and-authorization
