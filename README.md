# rails-module-i18n
> Rails module for basic internationalization.

## Step by step:
+ config/application.rb
```ruby
Rails.application.config.i18n.default_locale = :zh
```

+ add zh.yml to locals dirs:

+ generatel test page:
```bash
rails g controller pages welcome
```

## resources:
+ http://guides.rubyonrails.org/i18n.html
+ http://www.imooc.com/video/5847
+ https://github.com/svenfuchs/rails-i18n