[Twitter Bootstrap translated to portuguese](http://alexanmtz.github.com/bootstrap/)
=================

PROGRESS: 100% of translated strings

This is a portuguese translated unofficial version of Twitter Bootstrap.

Esta é uma versão não oficial traduzida do Twitter Bootstrap. 

This script can be used to translate bootstrap to any language, just changing a json of key : translation file and execute the right commands to generate the docs in the desired language

you can use `make translate [lang]` and `make gh-pages-translated`. The last command create a folder one step back at tree structure, and you can have a static generated page.

[Tutorials do Bootstrap em português](http://blog.alexandremagno.net/category/bootstrap-2/)

TRANSLATE FOR YOUR LANGUAGE
[Translating Bootstrap](https://github.com/alexanmtz/bootstrap/wiki/Translate-to-your-language)

The internationalization structure is located at `i18n` branch.

Os arquivos referentes a internacionalização estão na branch `i18n`
 

[Twitter Bootstrap](http://twitter.github.com/bootstrap)
=================

Bootstrap provides simple and flexible HTML, CSS, and Javascript for popular user interface components and interactions. In other words, it's a front-end toolkit for faster, more beautiful web development. It's created and maintained by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat) at Twitter.

To get started, checkout http://twitter.github.com/bootstrap!



Quick start
-----------

Clone the repo, `git clone git://github.com/twitter/bootstrap.git`, or [download the latest release](https://github.com/twitter/bootstrap/zipball/master).



Versioning
----------

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, Bootstrap will be maintained under the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the follow format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org/.



Bug tracker
-----------

Have a bug? Please create an issue here on GitHub! Also, when filing please make sure you're familiar with [necolas's guidelines](https://github.com/necolas/issue-guidelines). thanks! <3

https://github.com/twitter/bootstrap/issues



Twitter account
---------------

Keep up to date on announcements and more by following Bootstrap on Twitter, [@TwBootstrap](http://twitter.com/TwBootstrap).



Blog
----

Read more detailed announcements, discussions, and more on [The Official Twitter Bootstrap Blog](http://blog.getbootstrap.com).



Mailing list
------------

Have a question? Ask on our mailing list!

twitter-bootstrap@googlegroups.com

http://groups.google.com/group/twitter-bootstrap



IRC
---

Server: irc.freenode.net

Channel: ##twitter-bootstrap (the double ## is not a typo)



Developers
----------

We have included a makefile with convenience methods for working with the Bootstrap library.

+ **dependencies**
Our makefile depends on you having recess, uglify.js, and jshint installed. To install, just run the following command in npm:

```
$ npm install recess uglify-js jshint -g
```

+ **build** - `make`
Runs the recess compiler to rebuild the `/less` files and compiles the docs pages. Requires recess and uglify-js. <a href="http://twitter.github.com/bootstrap/less.html#compiling">Read more in our docs &raquo;</a>

+ **test** - `make test`
Runs jshint and qunit tests headlessly in phantom js (used for ci). Depends on having phatomjs installed.

+ **watch** - `make watch`
This is a convenience method for watching just Less files and automatically building them whenever you save. Requires the Watchr gem.


Contributing
------------

Please make all pull requests against wip-* branches. Also, if your unit test contains javascript patches or features - you must include relevant unit tests. Thanks!


Authors
-------

**Mark Otto**

+ http://twitter.com/mdo
+ http://github.com/markdotto

**Jacob Thornton**

+ http://twitter.com/fat
+ http://github.com/fat



Copyright and license
---------------------

Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
