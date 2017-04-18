# Example of [BlogoText](https://github.com/BlogoText/blogotext) addon for developers
Addons are available on [BlogoText/blogotext-addons](https://github.com/BlogoText/blogotext-addons)
Some documentation are available on [the BlogoText wiki](https://github.com/BlogoText/blogotext/wiki)
About [contributing](https://github.com/BlogoText/blogotext/wiki/Contributing)

---

Few rules apply here:


### Rule 1 - Fold

One addon by folder.

### Rule 2 - English

Write all in english.

### Rule 3 - PSR-2

Before spreading the world with your addon, make sure it is PSR-2 compliant.
You can download this [useful tool](https://github.com/squizlabs/PHP_CodeSniffer) to help you:

    curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcs.phar
    php phpcs.phar --standard=PSR2 -np --extensions=php --tab-width=4 --encoding=utf-8 --colors "<path to the addon>/<addon>.php"

Example with this calendar addon:

    php phpcs.phar --standard=PSR2 -np --extensions=php --tab-width=4 --encoding=utf-8 --colors calendar/

### Rule 4 - GL & HF !

That's enough! Good Luck and Have Fun :)