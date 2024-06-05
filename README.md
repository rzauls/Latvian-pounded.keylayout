Latvian keyboard layout for Mac OS X
============================================

Mac OS X Latvian keyboard layout with following changes from default:

    - `£ <=> #` swapped
    - `Alt/Option + <key>` for special characters
    - Does not support leader-`'` driven special characters (intentionally)

Instalation
-----------

````terminal
git clone git://github.com/rzauls/Latvian-pounded.keylayout
cd Latvian-pounded.keylayout
sudo cp Latvian-pounded.* ~/Library/Keyboard\ Layouts/
````

After executing this in terminal open "System Preferences" -> "Keyboard" -> "Input Sources..."

Under languages select "Other" and select the new input source "Latvian-pounded".

Activate the layout by either removing all other layouts, or using the top bar selector.

Credits
-------

Layout originally forked from [duksis](https://github.com/duksis/Latvian-pounded.keylayout)
