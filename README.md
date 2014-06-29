# Ridgepole

Ridgepole is a tool to DB schema.

It defines DB schema using [Rails DSL](http://guides.rubyonrails.org/migrations.html#types-of-schema-dumps), and updates DB schema according to DSL.
(like Chef/Puppet)

[![Gem Version](https://badge.fury.io/rb/ridgepole.png)](http://badge.fury.io/rb/ridgepole)
[![Build Status](https://drone.io/github.com/winebarrel/ridgepole/status.png)](https://drone.io/github.com/winebarrel/ridgepole/latest)

## Installation

Add this line to your application's Gemfile:

    gem 'ridgepole'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ridgepole

## Usage

```sh
ridgepole --export -o Schemafile
vi Schemafile
ridgepole --apply --dry-run
ridgepole --apply
```

## Demo

* [asciinema.org/a/9349](https://asciinema.org/a/9349)

## Example project

* https://github.com/winebarrel/ridgepole-example
  * https://github.com/winebarrel/ridgepole-example/pull/1
  * https://github.com/winebarrel/ridgepole-example/pull/2
