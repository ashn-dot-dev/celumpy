Celumpy
=======

An implementation of a [Celeste](https://www.celestegame.com/)-like physics
system as described in Madeline Thorson's
[*Celeste & TowerFall Physics*](https://www.maddymakesgames.com/articles/celeste_and_towerfall_physics/index.html)
with additional implementations of select mechanics from described in Thorson's
[*Celeste & Forgiveness*](https://maddymakesgames.com/articles/celeste_and_forgiveness/index.html).

This implementation is written in
[Lumpy](https://github.com/ashn-dot-dev/lumpy)
using the builtin
[Minimalist Lumpy Game Framework](https://github.com/ashn-dot-dev/lumpy/tree/main/lib/minimalist-game-framework)
library.

## Demo Video

https://github.com/user-attachments/assets/f72930f7-8e24-4035-b298-9e4a25cc273d

## Building & Running

[Install Lumpy](https://github.com/ashn-dot-dev/lumpy/tree/main?tab=readme-ov-file#installing)
and then set up a development enviroinment with the commands:

```
/path/to/celumpy$ python3 -m venv .venv-celumpy
/path/to/celumpy$ . .venv-celumpy/bin/activate
(.venv-celumpy) /path/to/celumpy$ python3 -m pip install -r requirements.txt
```

Run the demo with:

```
(.venv-celumpy) /path/to/celumpy$ $LUMPY_HOME/lumpy.py main.lumpy
```

## License
All content in this repository, unless otherwise noted, is licensed under the
Zero-Clause BSD license.

See LICENSE for more information.
