Bootstrap Nuget Packages
=================

[![Join the chat at https://gitter.im/sirkirby/twitter-bootstrap-nuget](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/sirkirby/twitter-bootstrap-nuget?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Most package content files are directly from the officially released source on the twbs/bootstrap repository https://github.com/twbs/bootstrap.

## Build ##
From the root directory via the command line

Install the grunt cli tools globally if not already installed

`npm install -g grunt-cli`

Install the required modules

`npm install`

Build the packages to the `dist` folder for local distribution

`grunt`

## Installing ##
Install commands entered from within the Visual Studio nuget package manager powershell console

**[Twitter.Bootstrap](http://nuget.org/packages/Twitter.Bootstrap)**
As of the v3.0.1 release of bootstrap all users of this package will be redirected to the new Bootstrap package that ships with Visual Studio 2013. The new package will be maintained by the Outercurve foundation just like many other popular packages on nuget, like jQuery. For more info visit http://chriskirby.net/bootstrap-nuget-package-moving-to-outercurve/

`PM> install-package Bootstrap`

**[Twitter.Bootstrap.Less](http://nuget.org/packages/Twitter.Bootstrap.Less)**
Package is based on the [twbs/boostrap](https://github.com/twbs/bootstrap) LESS source files. Installing will enable you to make your own modifications and compile the results.

If using Visual Studio, I recommend installing the latest version of the [Web Essentials](http://vswebessentials.com/) extension. It will compile and minify the less files automatically and provide a real time preview of your changes at design time.

`PM> install-package Twitter.Bootstrap.Less`

**[Twitter.Bootstrap.MVC](https://www.nuget.org/packages/Twitter.Bootstrap.MVC/)**
This package is meant to replace or complement the `Bootstrap` package for those using MVC 5.1. Upon installation it adds bundling and minification support for easy integration into your shared layouts and views. 

For more information on bundling and minification in MVC visit http://www.asp.net/mvc/tutorials/mvc-4/bundling-and-minification

`PM> install-package Twitter.Bootstrap.MVC`

**For MVC 4**
`PM> install-package Twitter.Bootstrap.MVC -version 2.0.0`

Versioning
----------
All release versions correspond with the bootstrap repository's `<major>.<minor>.<patch>` semantic format.

License
---------------------
* For this repo: [License](LICENSE.txt)
* For Bootstrap (as of v3.1.0): http://opensource.org/licenses/MIT
* For bootstrap source see https://github.com/twbs/bootstrap/blob/master/README.md
