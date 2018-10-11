# Static Valet Driver 

Valet driver for serving static php files. By default, laravel valet will reroute all requests to the index.php file in the public folder.

This driver will route all file requests to their appropriate files.

To enable the drive, simply create a `static` file in the root of the project. This file can be added to the gitignore to ensure it isn't committed.

To add the driver, simply copy the `StaticValetDriver.php` file to your `~/.config/valet/Drivers` folder.
