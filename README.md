# TV Remote Simulator

An object-oriented Python simulation of a television and remote control, modeling real-world device behavior and state management.

## Features
- Power, mute, channel, and volume controls
- Variable handling (e.g., channel wraps around at min/max, mute overrides volume changes)
- Takes in internal state using private attributes

## Built With
- Python (Object-Oriented Programming)

## How to Run
Import the `Television` class and interact with it, e.g.:
```python
from television import Television

tv = Television()
tv.power()
tv.channel_up()
print(tv)
```
