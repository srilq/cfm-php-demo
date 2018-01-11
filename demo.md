# copilot-markdown-generator PHP Demo

### 1. <br>There is a [GitHub repo] called copilot-markdown-generator-php, a [README.md] and a [CONTRIBUTING.md].
---
### 2. <br>There are [API docs] in the readme file.
---
### 3. <br>It's published on [Packagist]. The package is defined in [composer.json].
---
### 4. <br>You can install it:
```
~/src/cfm-php-demo
❯ composer require conde-nast-international/copilot-markdown-generator
```
---
### 5. <br>You can run it interactively:
```
~/src/cfm-php-demo
❯ php -a
Interactive shell

php > require __DIR__.'/vendor/autoload.php';
php > $link = new CopilotTags\Link("Tugboat", "https://github.com/conde-nast-international/tugboat");
php > echo $link->write();
[Tugboat](https://github.com/conde-nast-international/tugboat)
```
```
~/src/cfm-php-demo
❯ php -a
Interactive shell

php > require __DIR__.'/vendor/autoload.php';
php > $blockquote = new CopilotTags\Blockquote("Hello!\nWorld!");
php > echo $blockquote->write();

> Hello!
> World!
```

[GitHub repo]: https://github.com/conde-nast-international/copilot-markdown-generator-php/
[README.md]: https://github.com/conde-nast-international/copilot-markdown-generator-php/blob/master/README.md
[CONTRIBUTING.md]: https://github.com/conde-nast-international/copilot-markdown-generator-php/blob/master/CONTRIBUTING.md
[API docs]: https://github.com/conde-nast-international/copilot-markdown-generator-php/blob/master/README.md#api
[Packagist]: https://packagist.org/packages/conde-nast-international/copilot-markdown-generator
[composer.json]: https://github.com/conde-nast-international/copilot-markdown-generator-php/blob/master/composer.json
