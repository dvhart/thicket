# Laubwerk Importer for Blender

This project implements a Python plugin to import Laubwerk plant models into Blender. It facilitates the Python Extension delivered with all versions of the Laubwerk Player Plugin. It can be used with all Laubwerk Plants Kits, including the [Laubwerk Plants Kit Freebie](http://www.laubwerk.com/store/plants-kit-freebie).

![doc/acerp-cycles.png](doc/acerp-cycles.png)

## What is this repository for?

This repository contains the latest version of the plugin and can be used to contribute improvements.

This project is an updated fork of https://bitbucket.org/laubwerk/lbwbl.

## How do I get set up?

### Prerequisites

* You will need to have the Laubwerk Player Plugin (which is part of every Laubwerk Plants Kit) installed, so the Laubwerk Python Extension is available. If you do not have Laubwerk Plants already installed, you can grab the Plants Kit Freebie [from the Laubwerk website](http://www.laubwerk.com/store/plants-kit-freebie).
* A current version of [Blender](http://www.blender.org/). The plugin is known to run with [Blender 2.80](http://www.blender.org/features/past-releases/2-80/).

### Installation
* Ensure the Laubwerk python module is in your PYTHONPATH
  * Mac: PYTHONPATH=/Library/Application Support/Laubwerk/Python
  * Windows: TODO
* After Blender has been started at least once the addon folder will have been created. Clone the git repository into that folder and change the name of the repository folder to `io_import_laubwerk`.
  * Mac: `~/Library/Blender/2.80/scripts/addons`
  * Windows: `%AppData%/Blender Foundation/2.80/scripts/addons` (TODO: verify)
* When restarting Blender, it will see the plugin, but it will be disabled by default. Choose `File -> User Preferences...` to bring up the Preferences window. Select the *Addons* Tab and look for the Laubwerk Addon in the list (search for `laubwerk`). Enabling the checkbox will load the Addon.
* Clicking the `Save User Settings` button at the bottom of the Preferences window makes sure Blender remembers this setting.
* After you did this, the Laubwerk import Addon is available through `File -> Import -> Laubwerk Plant (.lbw.gz)`.
* See the Blender Wiki for more general information about [Blender Add-Ons](https://wiki.blender.org/wiki/Process/Addons).

### Who do I talk to? ###
See [CONTRIBUTING](CONTRIBUTING.md) for more information.
