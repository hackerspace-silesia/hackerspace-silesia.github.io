# Hackerspace Silesia homepage

To run it locally you will need Ruby.
Install it using https://rvm.io/ or https://github.com/sstephenson/rbenv or just use your system one.

```
bundle install
jekyll serve --watch
```

After bundle you can run Guard in separated console:
```
guard
```

Use LiveReload plugin (Chrome, Firefox) and you can forget about reloading the page.

That's it.

More to read about jekyll: http://jekyllrb.com/

To deploy your changes, just push commit to github master branch, site will be automatically regenerated.

[![Build Status](https://travis-ci.org/hackerspace-silesia/hackerspace-silesia.github.io.svg?branch=jekyll)](https://travis-ci.org/hackerspace-silesia/hackerspace-silesia.github.io)
