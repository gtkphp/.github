
# Welcome, Learn a little about GTK+PHP


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
--------------------------------------
```bash
sapi/gui/php -f about.gtk
```
<img src="https://raw.githubusercontent.com/gtkphp/.github/main/profile/gtkml.png" />

@official http://gtk.php.net/
@see https://github.com/php/php-gtk-src
