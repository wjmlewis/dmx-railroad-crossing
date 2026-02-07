This is a DMX Light (DMX being the protocol for stage lighting) that is meant to look like a American railroad crossing light! It uses an ESP-32 S3 as the brains of the build, and a MAX485 for the DMX control. It's powered by a 12v power supply, which uses a 5V 10A step down (these LEDs use a lotta amps!!) And finally the firmware uses open source project, WLED! It features an app, DMX control and importantly, a software current limiter (there is a 10A physical fuse just in case😉)

I'm making this project as a kids event near me is putting on a 4 day club with a wild west theme, and they wanted some railroad level crossing lights that use their existing DMX controller!

Talking of DMX controllers, this project can be used via the WLED app, a web server or DMX!
