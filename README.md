# ruby101
## Short Course

This repository contains material and website for a short 
introduction to Ruby

## Building the website

The static website is generated using [middleman](https://middlemanapp.com)

Install this on your own computer, then clone the repository:
```
git clone https://github.com/nairuby/ruby101
```

The webpage source code is in the
[source](https://github.com/nairuby/ruby101/tree/source) branch

to make changes to it use
```
cd ruby101
git checkout source
```

then make changes. To generate the website use
```
middleman build
```

To push source code changes use
```
git commit -am "Useful commit message"
git push
```

The website itself is in the 
[gh-pages](https://github.com/nairuby/ruby101/tree/gh-pages) branch.
To push the updated website use
```
git subtree push --prefix build origin gh-pages
```
