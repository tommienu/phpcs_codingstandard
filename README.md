phpcs_codingstandard
====================

Personal coding standards for phpcs

OSX instructions:
* curl -O http://pear.php.net/go-pear.phar
* sudo php -d detect_unicode=0 go-pear.phar
* * Type 1 and press return.
* * Enter: /usr/local/pear
* * Type 4 and press return.
* * Enter: /usr/local/bin
* * Press return
* sudo pear upgrade-all;
* sudo pear install PHP_CodeSniffer;

Clone to /usr/local/share and run:
* sudo chmod -R 777 /usr/local/share/phpcs_codingstandard/
* phpcs --config-set default_standard /usr/local/share/phpcs_codingstandard/ruleset.xml

Update phpcs_additional_args in phpcs.sublime-settings and remove "--standard": """

---------------
OSX fix if include_once fails:
* Add /usr/local/pear/share/pear/PHP/ to include_path in php.ini
