# Magisk Manager
This is one of the submodules used in Magisk. The project is licensed under GPL v3 (or newer).
More info are written in the [Magisk Main Repo](https://github.com/topjohnwu/Magisk)

## Building Notes
You need to install CMake and NDK to build the zipadjust library.
There are several files required to let Magisk Manager work properly, and they can be copied by using the build script in the [Magisk Main Repo](https://github.com/topjohnwu/Magisk). These files are: `magisk_uninstaller.sh`, `util_functions.sh`, `public.certificate.x509.pem`, and `private.key.pk8` under the `app/src/main/assets` folder.

## License

```
MagiskManager, including all subprojects (git submodule) is free software:
you can redistribute it and/or modify it under the terms of the 
GNU General Public License as published by the Free Software Foundation, 
either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

## Credits

**MagiskManager**

* Copyright 2016-2017, John Wu (@topjohnwu)
* All contributors and translators
