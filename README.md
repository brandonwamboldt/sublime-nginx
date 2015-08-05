Nginx Syntax Highlighting Plugin
================================

This is a syntax highlighting plugin for Nginx configuration files in Sublime Text 2/3 that isn't completely broken. I was using the least broken plugin out there, [kvs/ST2Nginx](https://github.com/kvs/ST2Nginx), but it was pretty broken for my Nginx files.

With this plugin, I have fixed many of those bugs and will actively maintain and extend it, as I frequently work with Nginx.

Installation
------------

Simply [download](https://github.com/brandonwamboldt/sublime-nginx/archive/master.zip) and place in your Packages directory (Preferences > Browse Packages, download to User/).

Usage
-----

This package will recognize `*.conf`, `*.conf.erb`, `nginx.conf`, `mime.types`, and `fastcgi_params` by default. 
Use `Tools/Command Palette ... (Ctrl+Shift+P)` and type `se sy ngi` to `Set Syntax` to `nginx` manually.

Use `Goto/Goto Symbol ... (Ctrl+R)` to open the panel and input your search (fuzzy) to jump to expected `location`, `server`, `http` etc.

Screenshots
-----------

![screenshot](screenshot.png?raw=true "Screenshot using SpaceGray theme")

![screenshot](screenshot2-custom-theme.png?raw=true "Screenshot with function list panel, using custom Soda theme")
