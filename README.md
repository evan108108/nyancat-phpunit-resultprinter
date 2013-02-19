[![Nyan Cat result printer for PHPUnit](https://github.com/whatthejeff/nyancat-phpunit-resultprinter/raw/master/nyan.gif)](https://github.com/whatthejeff/nyancat-phpunit-resultprinter/raw/master/nyan.gif)

## Requirements

The Nyan Cat result printer for PHPUnit works with PHP 5.3.3 or later.

## Installation

Place nyancat-phpunit-resultprinter directory inside your Yii applications extionsions directory.  
Then update your protected/config/console.php 

```php
'import'=>array(    
    …            
	'ext.nyancat-phpunit-resultprinter.src.*',
	…
),
```

Once installed, add the following attributes to the `<phpunit>` element in your
`protected/tests/phpunit.xml` file:

    printerFile="../extensions/nyancat-phpunit-resultprinter/src/FabResultPrinter.php"
	printerClass="FabResultPrinter"

## Acknowledgements
Nyancat PHPUnit Result Printer For Yii Framework is a fork of [whatthejeff's](https://github.com/whatthejeff/nyancat-phpunit-resultprinter) amazing repo formatted for easy use with Yii Framework. 

The Nyan Cat result printer for PHPUnit was __heavily__ inspired by the
glorious [mocha/nyan.js](https://github.com/visionmedia/mocha/blob/master/lib/reporters/nyan.js).

## License

The Nyan Cat result printer for PHPUnit is licensed under the [MIT license](LICENSE).