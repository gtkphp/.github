
# Welcome, Learn a little about GTK+PHP


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
