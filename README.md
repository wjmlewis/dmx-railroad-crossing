This is a **DMX Light** (DMX being the protocol for stage lighting) that is meant to look like a American railroad crossing light! It uses an ESP-32 S3 as the brains of the build, and a MAX485 for the DMX control. It's powered by a 12v power supply, which uses a 5V 10A step down (these LEDs use a lotta amps!!) And finally the firmware uses open source project, WLED! It features an app, DMX control and importantly, a software current limiter (there is a 10A physical fuse just in case😉)

I'm making this project as a kids event near me is putting on a 4 day club with a wild west theme, and they wanted some railroad level crossing lights that use their existing DMX controller!

Talking of DMX controllers, this project can be used via the WLED app, a web server or DMX!

<img width="956" height="440" alt="image" src="https://github.com/user-attachments/assets/72eb417e-953a-4ed9-858f-c7c0d0f801e7" />

<img width="893" height="546" alt="image" src="https://github.com/user-attachments/assets/56f835d2-e107-405c-90ee-fc337a98280f" />

Here's the wiring diagram as well!

<img width="1103" height="659" alt="image" src="https://github.com/user-attachments/assets/05dee017-e628-4d1b-9e9c-f3d93fe56ff6" />



And heres the Bill of Materials: (the quantity is the amount i'll actually be using)

12V to 5v 10A Step down (1pcs)

5 terminal WAGO Connectors (2pcs)

Heat Shrink Tubing (a bunch)

20AWG Wire (also a lot)

WS2812B 54LED 73mm Ring (2pcs)

12V Power Supply (1pcs)

ESP32 S3 Dev Board + Expansion Board (1pcs)

MAX485 Module (1pcs)

3 Pin XLR Male + Female Connector (2pcs)

16V 1000UF Aluminum Capacitors (at least 2pcs)

Resistors (at least 2pcs)

10A Glass Fuses (1pcs)

Glass Fuse Holders 5x20mm (1pcs)

Screw Set	(1pcs)

Tracing Paper (from my drawer)

Hot Glue (also from my drawer)

