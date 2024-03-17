# pith-pack-jscrollpane
Pack the jScrollPane jQuery plugin to use with Pith

-------

# About

This project packs jScrollPane so that it can be used on the front-end with the Pith Framework.

For info on jScrollPane, see the jScrollPane Git repo at https://github.com/vitch/jScrollPane.

For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-jscrollpane
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call jScrollPane resources from
    ['route', 'GET', '/resources/vendor/library/jscrollpane/{filepath:.+}', '\\PithFront\\PithPackJscrollpane\\JscrollpaneResourceRoute'],
];
```

-------------


# Licensing Info


### jScrollPane 
#### Licensing Info
- jScrollPane 2.2.3 RC 2
- jScrollPane is dual-licensed under the GPL 2 license and the MIT license. 
- Copyright (c) 2010 Kelvin Luck. Copyright (c) 2017-2020 Tuukka Pasanen. 
- Git Repo: https://github.com/vitch/jScrollPane


### pith-pack-jscrollpane
#### Licensing Info
- pith-pack-jscrollpane (using jScrollPane)
- The MIT License (MIT)
- Copyright (c) Ian Maurmann
- Link: https://github.com/pith-front/pith-pack-jscrollpane


