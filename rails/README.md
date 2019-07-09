## Rails Templates

Quickly generate a rails app with a default configuration using
[Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).

### Default

Rails app including a Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/trouni/templates/master/rails/default.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
