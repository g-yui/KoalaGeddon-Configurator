# Koalageddon-Configurator
A extremely simple configuration tool for @acidicoala 's Koalageddon.

# Features
- Simple TTK GUI with the Breeze theme.
- Will modify the configuration file (Config.jsonc) for each platform, by enabling or disabling injection and replication and by adding or removing id's from the blacklist.
- Simple ID searcher for Steam 
> The max number of results refers to each of the options available for the search, all duplicates are removed before displaying, as such, you may see a lower number of results overall.
- Pictures bloody everywhere 😄

# Installation/Usage
- Install Koalageddon and run it at least once, this will create the Config file that this GUI modifies.
- Download and run the compiled binaries for the GUI from [here](https://github.com/g-yui/KoalaGeddon-Configurator/releases).
- You can run from source without the need for a specific pyenv, just use pip to install the requirements via either pipfile or requirements.txt and then run main.py.

# Plans for the future
> - If you're wondering about the progress of the qt release, I've been rather busy, so probably not anytime soon, I'll still be fixing any bugs that get reported though. Thanks for using this small GUI!
- Since this has somehow managed to get into the releases section I'm planning a complete reformatting of the code, and a change from Tkinter to PyQt5, which would make the whole GUI part look and function better, plus refactor the scripts to make them more ordered, way more than having just a single main.py file :)
- The following features are planned for the Qt Release:
> - Better performance
> - Better feedback to the user
> - View current values
> - Support for themes and translations (since it's relatively easy to do) <br />
> - Origin/EA Desktop search (via the [entitlements.json](https://github.com/acidicoala/public-entitlements/blob/main/origin/v1/entitlements.json) file) <br />
> - Known Uplay entitlements (via the [products.jsonc](https://github.com/acidicoala/public-entitlements/blob/main/ubisoft/v1/products.jsonc) file) <br />
> - Better Steam search <br />
> - Epic Store search (help needed understanding GraphQL with Python for this one) <br />
> - A Koalageddon update checker (will make a check by downloading the latest Config.jsonc to see if there's a change between the versions of the local config_version variable, after that it will delete the file and prompt to install if appropriate) <br />
> - unlock_dlc support for steam <br />
> - Better error handling <br />
> - Ignore and terminate options if "Advance options" boolean is enabled via custom config file for this GUI :) <br />

# Known bugs
- Interface can get buggy if too many IDs are changed at once.
- Rather slugish at times.

# Requirements/Licences
- Pillow, licensed under the open source HPND license.
- TtkThemes, licensed under a GNU GPLv3 compatible license.
- Requests, licensed under the Apache Software license (Apache 2.0).
- JsoncParser, licensed under the MIT license.

# Acknowledgments
- Acidicoala for the creation of such a great tool and the immense help provided for the betterment of this one.
- What's up Jeddunk ;)
