= Rower

This is ruby wrapper for [bower](http://bower.io/) package manager (Rower goes to ruby bower). It allows to configure your application assets with one file.
__Let's row!!!__


The idea
========
The idea is to have one `Rowerfile` where you will specify all assets requirements in DSL maner. 

For Rails project it can be something like this:

```ruby
folder 'app/assets'                    # it can be path, current_folder
javascript_folder  'javascripts/vendor' # js
stylesheets_folder 'stylesheets/vendor' # css

bower do
  install 'jquery'
  install 'bootstrap'
end
```


== Copyright

Copyright (c) 2014 A.S. Lomoff. See LICENSE.txt for
further details.
