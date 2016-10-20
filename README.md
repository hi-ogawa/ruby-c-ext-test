```
$ ruby -v
ruby 2.3.1p112 (2016-04-26 revision 54768) [x86_64-darwin14]
$ ruby run_mkmf.rb
creating Makefile
$ make
compiling something.c
linking shared-object something.bundle
$ ruby test.rb
```

# TODO

- module with pure function
- class and object instantiation
- dependency to system shared library
- consideration for ruby garbage collection

# Reference

- lib/mkmf.rb
- doc/extension.rdoc
- ext/digest/
- math.c
- https://github.com/puma/puma
- http://guides.rubygems.org/gems-with-extensions/
