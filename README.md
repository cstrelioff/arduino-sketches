# arduino-sketches

A repository for my arduino sketches. I have an unusual setup on Ubuntu 14.04,
using make instead of the standard Arduino IDE-- if you'd like to read about it
[checkout my blog post](http://chrisstrelioff.ws/sandbox/2015/12/08/arduino_on_ubuntu_14_04_without_the_arduino_ide.html).

## Using the examples

Using the setup detailed in the blog post, each example can be compiled and
uploaded to the Arduino using the following procedure:

* Connect the Arduino via USB
* Find the port used by the Arduino (see blog post for help)
* Edit **makefile** to use the port found above
* In terminal-- change directory to project and compile:

```bash
$ make
``` 
followed by upload (if no errors):

```bash
$ make upload
```
