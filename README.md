# Formtastic jQuery Inputmask
Easily add jquery inputmask to your Formtastic (or ActiveAdmin).

## Installation
**1. Include to your Gemfile**
```ruby
gem 'formtastic-jquery_inputmask'
```

**2. Require javascript dependency**
```javascript
//= require formtastic/inputmask
```

**3. Load locale or other [inputmask](https://github.com/guilhermereis1/formtastic-jquery_inputmask/tree/master/vendor/inputmask/dist) file as you want**
```javascript
//= require formtastic/inputmask/locales/pt-BR
//= require inputmask/phone-codes/phone-us
```

*p.s. it auto adds jquery as a dependency in your project*

## Usage
```ruby
f.input :created_at, mask: 'datetime'
f.input :date, mask: { alias: 'datetime', inputformat: 'dd/mm/yyyy' }
```

## Maintainer
[Guilherme Reis](https://github.com/guilhermereis1)

## Credits

Thank you [contributors](https://github.com/guilhermereis1)!

<img src="https://avatars1.githubusercontent.com/u/23090707?s=400&u=acfb62d689e4141440b7ef56add07322352be493&v=4" alt="Guilherme Reis" width="250"/>

activeadmin_addons is maintained by [guilhermereis1](https://github.com/guilhermereis1).

## License

ActiveAdminAddons is © 2018 Guilherme Reis. It is free software and may be redistributed under the terms specified in the LICENSE file.
