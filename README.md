phpcs_codingstandard
====================

Personal coding standards for phpcs

OSX instructions:
* sudo cp /private/etc/php.ini.default /private/etc/php.ini;
* sudo php /usr/lib/php/install-pear-nozlib.phar;
* pear config-set php_ini /private/etc/php.ini;
* pecl config-set php_ini /private/etc/php.ini;
* sudo pear upgrade-all;
* sudo pear install PHP_CodeSniffer;
* nano /private/etc/php.ini; -> add: include_path = ".:/php/includes:/usr/lib/php/pear/"

Clone to /usr/local/share and run:
* phpcs --config-set default_standard /usr/local/share/phpcs_codingstandard/ruleset.xml

Update phpcs_additional_args in phpcs.sublime-settings and remove "--standard": """
