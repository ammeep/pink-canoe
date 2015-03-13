Pink Canoe
==========
Pink Canoe is an elegant, clean & white minimal and responsive theme for [Octopress](http://octopress.org) and originally a fork of the OctoPress CleanPress Theme.

Check out the theme in action [here](http://amy.palamounta.in).


Install
-------
    $ cd octopress
    $ git clone git://github.com/ammeep/pink-canoe.git .themes/pink-canoe
    $ rake install['pink-canoe']
    $ rake generate

Post Images
-------
By default, a place holder image will appear as your main post image. If you wish to override this with your own image then simply add the following to the header of your post's markdown file.

For exmaple 

```
image: /images/featured/clam-shell.jpg
```

leaving you with a header metadata that looks like this

````
---
title: Clams
author: ammeep
layout: post
image: /images/featured/clam-shell.jpg
---
```

Post Summary
-------
By default, the first 400 characters of your post will apear as your default post summary. If you wish to override this with your own summary then simply add the following to the header of your post's markdown file.

For exmaple 

```
summary: Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a
```

leaving you with a header metadata that looks like this

````
---
title: Clams
author: ammeep
layout: post
summary: Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a
---
```

Font
---------------------
The font is currently using Proxima Nova from Typekit, if you don't set this up the fall back is Helvetica Neue.

If you spot any errors then let me know, alternatively take it on and make it better!
