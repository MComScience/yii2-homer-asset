# yii2-homer-asset
Bootstrap theme for Yii2 Advanced Application Template

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Install

```
composer require m-comscience/yii2-homer-asset
```

## Usage

Config Component: `frontend/config/main.php` or `backend/config/main.php`
```php
'components' => [
    // ...
    'view' => [
        'theme' => [
            'pathMap' => [
                //'@homer/views' => '@common/themes/custom-theme/views', // override view
                '@app/views' => '@homer/views',
            ],
        ],
    ],
],

```
