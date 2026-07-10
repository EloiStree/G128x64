# G128x64

> A lightweight Godot application dedicated to displaying an SSD1306 screen on any platform.

I've always been a big fan of the simplicity of the SSD1306 display.
Imagine my surprise when I discovered that the Flipper Zero is built around one.

I found the idea of creating an engine in GDScript powered by nothing more than a 128×64 boolean array fascinating.  
It keeps the rendering logic simple, portable, and fun to experiment with.   

If you're targeting real hardware, you'll find both CircuitPython and ESP32 examples to drive an actual SSD1306 display.   
https://github.com/EloiStree/2026_04_27_esp32_oled_128x64_udp_i2c   

If you simply want to render an SSD1306 screen on Android, Android TV, Raspberry Pi, desktop, or virtually any platform supported by Godot, this application has you covered.
