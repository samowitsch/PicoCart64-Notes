# PicoCart64-Notes

Some collected information about [PicoCart64](https://github.com/kbeckmann/PicoCart64) (Nintendo 64 flash cart using a Raspberry Pi Pico / RP2040).

## Links

* [Github: PicoCart64 Project by Konrad Beckmann](https://github.com/kbeckmann/PicoCart64)
* [Hack64 - N64 ROM Swapper: .n64/.v64 to .z64](https://hack64.net/tools/swapper.php)
* [PicoCart64 UF2 ROM Builder](https://kbeckmann.github.io/PicoCart64/)

## Variants

### PicoCart64 lite by Konrad Beckmann

![images/picocart64-konrad-beckmann/picocart64-lite-top.jpeg](images/picocart64-konrad-beckmann/picocart64-lite-top.jpeg)
![images/picocart64-konrad-beckmann/picocart64-lite-bottom.jpeg](images/picocart64-konrad-beckmann/picocart64-lite-bottom.jpeg)

### PicoCart64 by YueCheng

![images/picocart64-yue-cheng/picocart64-yue-cheng-top.avif](images/picocart64-yue-cheng/picocart64-yue-cheng-top.avif)
![images/picocart64-yue-cheng/picocart64-yue-cheng-bottom.avif](images/picocart64-yue-cheng/picocart64-yue-cheng-bottom.avif)

### PicoCart64 the pragmatic way by [XGAMES VIDEOJUEGOS](https://www.youtube.com/@DAVIDXGAMESmx)

![images/picocart64-on-plain-game-pcb/DIAGRAMA-PICO-ORIGINAL.png](images/picocart64-on-plain-game-pcb/DIAGRAMA-PICO-ORIGINAL.png)
![images/picocart64-on-plain-game-pcb/picocart64-diagrama.png](images/picocart64-on-plain-game-pcb/picocart64-diagrama.png)

## Pico board pinouts

### RPI Pico

![pinout/raspberry-pico-pinout.png](pinout/raspberry-pico-pinout.png)

### WeAct RP2040

![pinout/weact-rp2040-pinout.webp](pinout/weact-rp2040-pinout.webp)

### Bitfunx Picoboot RP2040

![pinout/bitfunx-pinout.png](pinout/bitfunx-pinout.png)

## Workarounds/Troubleshooting for problems

### WeAct RP2040

If WeAct on PicoCart64 lite will not work try to remove the BSS84 and solder a jumper wire to VSYS. Also the removed jumper JP1 worked for me. 

> **⚠️ Important:** the BSS84 acts like a protection(?) for the N64. If removed do not flash a game rom onto PicoCart64 lite if inserted into N64 over USB cable.

![images/workarounds/pico-weact-board-jumper-to-vsys.jpg](images/workarounds/pico-weact-board-jumper-to-vsys.jpg)

### Bitfunx Picoboot RP2040

If Bitfunx on PicoCart64 lite will not work try to remove the BSS84 and solder a jumper wire to VBUS.

> **⚠️ Important:** the BSS84 acts like a protection(?) for the N64. If removed do not flash a game rom onto PicoCart64 lite if inserted into N64 over USB cable.

![images/workarounds/pico-bitfunx-board-jumper-to-vbus.jpg](images/workarounds/pico-bitfunx-board-jumper-to-vbus.jpg)

## Cartridge case

> [Thingiverse: N64 Cartridge (Retrostage/ N64 Blaster)
](https://www.thingiverse.com/thing:4462321)

![/images/cartridge/IMG_5508.jpg](/images/cartridge/IMG_5508.jpg)
![/images/cartridge/IMG_5509.jpg](/images/cartridge/IMG_5509.jpg)