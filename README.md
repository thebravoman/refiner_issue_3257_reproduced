For reproducing 
https://github.com/refinery/refinerycms/issues/3257

```
bundle install
rails s
```

Then go to localhost:3000 and the following error occurs

```ruby
Showing /home/myusername/.rvm/gems/ruby-2.2.2/bundler/gems/refinerycms-f8a1152f9d25/core/app/views/refinery/_site_bar.html.erb where line #3 raised:

Incompatible units: 'px' and 'rem'.

```

