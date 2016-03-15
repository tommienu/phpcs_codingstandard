phpcs_codingstandard
====================

Personal coding standards for phpcs

OSX instructions:
* curl -O http://pear.php.net/go-pear.phar
* sudo php -d detect_unicode=0 go-pear.phar
* sudo pear upgrade-all;
* sudo pear install PHP_CodeSniffer;

Clone to /usr/local/share and run:
* phpcs --config-set default_standard /usr/local/share/phpcs_codingstandard/ruleset.xml

Update phpcs_additional_args in phpcs.sublime-settings and remove "--standard": """
