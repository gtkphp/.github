
# Welcome, Learn a little about GTK+PHP
```php
<?php use Gtkml\Window as MainWindow; ?>
<!DOCTYPE application PUBLIC "-//PHP//DTD PHPML 1.0//EN" "http://www.php.net/TR/phpml1/DTD/phpml1.dtd">
<application id="demo" xmlns="http://www.php.net/2022/gtkml"
                       xmlns:xi="http://www.w3.org/2001/XInclude">
    <link rel="stylesheet" href="styles.css">
    <?php include "copyright.phpml"; ?>
    <main-window>
        <xi:include href="content.phpml"/>
    </main-window>
</application>
```

<img src="https://raw.githubusercontent.com/gtkphp/.github/main/profile/my-window.png" />

```bash
sapi/gui/php about.php
```
<img src="https://raw.githubusercontent.com/gtkphp/.github/main/profile/gtkml.webp" />

--------------------------------------

```bash
sapi/gui/php minimal.php
```
<img src="https://raw.githubusercontent.com/gtkphp/.github/main/profile/gtkml-window.webp" />

--------------------------------------

```bash
sapi/cli/php -f ExampleApplication.gtk
```

```php
<?php
include "ExampleWindow.php"

$app = Gtk\Application::create($argc, $argv, "net.php.gtk");

$window = new ExampleWindow;

//Shows the window and returns when it is closed.
$status = $app->run($window);

exit($status);
```


@official http://gtk.php.net/
@see https://github.com/php/php-gtk-src
