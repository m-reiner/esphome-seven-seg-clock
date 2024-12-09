# esphome-seven-seg-clock
A re-creation of shiura's 'Monolithic Digital Clock / 7-segment Display Unit', which can be found on [Thingiverse](https://www.thingiverse.com/thing:5170654) and [Printables](https://www.printables.com/model/171312-monolithic-digital-clock-7-segment-display-unit).

I have confirmed that the [YAML file](https://github.com/m-reiner/esphome-seven-seg-clock/blob/main/seven-seg-clock.yaml) in this repository works as of ESPHome 2024.11.3.

I will update this readme with better instructions later, but for now all you need to do is print out shiura's files from either Printables or Thingiverse (links above), wire up your LEDs as they specify, create a new device in your instance of ESPHome, and then overwrite your newly-generated YAML file with my code.  Feel free to tweak where necessary, especially if you do not intend to recreate all the secret entries I use in my version.
