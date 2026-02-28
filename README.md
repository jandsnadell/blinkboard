# BlinkBoard Library

A simple CircuitPython library that controls the onboard LED on Raspberry Pi Pico.
Easy for beginners.
## Installation

1. Copy the `blinkboard-main/blinkboard-main` folder to `CIRCUITPY/lib/`.
2. Rename to `blinkboard`
3. Use as follows:
import blinkboard

### Documentation
There are four functions, on(), off(), toggle(), and blink(), and a speed variable for blink().
import blinkboard
blinkboard.speed = 1       # set blink speed in seconds
blinkboard.blink(5)        # blink 5 times, as an example
blinkboard.on()            # turn LED on
blinkboard.off()           # turn LED off
blinkboard.toggle()        # toggle LED state, same as on()/off(), but easier
