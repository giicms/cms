CMS
=================

Module CMS

## Installation

The preferred way to install this extension is through composer.

Either run

```
php composer.phar require "giicms/cms" "dev-master"
```
or add

```json
"giicms/cms": "dev-master"
```

to the require section of your application's `composer.json` file.

## Usage Example
~~~php

 'modules' => [
        'cms' => [
            'class' => 'giicms\cms\Module',
        ],
  ],
~~~
