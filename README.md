This is my repo for Home Assistant Projects, just to share with people who request it.

## Roku Remote Resources:
- [ESPHome Matrix Keypad Doc](https://esphome.io/components/matrix_keypad.html) – The main resource
- [Medium post about building a Roku remote with an Arduino](https://medium.com/@nchourrout/building-a-better-and-bulkier-roku-remote-fa34bcb185c3) – The original inspiration, but I veered off to go with ESPHome and HA instead of straight up arduino directly to TV
- [Handwiring a Mechanical Keyboard](https://www.crackedthecode.co/a-complete-guide-to-building-a-hand-wired-keyboard/) – The remote wiring is similar to this except DON'T ADD DIODES, they messed up the signals. Just wire them straight together in columns and rows.
- [D1 Mini Pro on AliExpress](https://www.aliexpress.us/item/2251832465432818.html?pdp_ext_f=%7B%22sku_id%22:%2212000029435238220%22%7D) – This is the one I used. Super cheap on Ali. I've already setup 3 of them in my home and they work so so well with ESPHome
