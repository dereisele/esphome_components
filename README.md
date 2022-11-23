# esphome_components

## ili9341

**NOT WORKING YET**

Fork of the original package https://github.com/esphome/esphome/tree/dev/esphome/components/ili9341
with add init code for **ili9342c**.
This Display is build into the [M5Stack Core *Gray*](https://docs.m5stack.com/en/core/gray).

The init bytes are obtained from:
https://github.com/m5stack/M5Stack/blob/master/src/utility/ILI9342C_Init.h

use it

```yaml
external_components:
  - source:
      type: git
      url: https://github.com/dereisele/esphome_components
    components: [ ili9341 ]
```
