# Week 1 · Make an LED obey you

Nov 2–8, 2026 · in the Wokwi simulator

**Wokwi project:** _paste the link here_

## Mission

- [ ] **Level 1 · Blink:** LED on for one second, off for one second, forever.
  Look up: `setup()`, `loop()`, `pinMode`, `digitalWrite`, `delay`.
- [ ] **Level 2 · Fade:** the LED smoothly brightens, then dims, on repeat.
  Look up: `analogWrite` on the ESP32.
- [ ] **Level 3 · Button:** the LED lights only while the button is held.
  Look up: `digitalRead`, the pin modes for inputs. Print the button value with `Serial.println`.
- [ ] **Stretch · Toggle:** each press switches the LED on or off. Describe what goes wrong before looking it up.

Parts in Wokwi: ESP32, LED, 220 Ω resistor, pushbutton. LED on GPIO 18, button on GPIO 4.

## Plan for the week (~7 h)

| Session | Time | What |
| --- | --- | --- |
| 1 | 1.5 h | Skim the Wokwi ESP32 guide, then Level 1 |
| 2 | 1.5 h | Level 2 |
| 3 | 1.5 h | Level 3, the stretch goal, the experiments |
| 4 | 0.5 h | Research the why-questions, write your answers |
| 5 | 2 h | Crop model task |

## Resources

**For the build**

- [Wokwi ESP32 guide](https://docs.wokwi.com/guides/esp32): how the simulated board works, pinout, serial monitor
- Level 1: [Espressif's Blink tutorial](https://docs.espressif.com/projects/arduino-esp32/en/latest/tutorials/blink.html), from the makers of the ESP32
- Level 2: [ESP32 PWM with Arduino IDE](https://randomnerdtutorials.com/esp32-pwm-arduino-ide/) (Random Nerd Tutorials). Use the `analogWrite` part first; the `ledc` functions are the advanced version.
- Level 3: [ESP32 Digital Inputs and Outputs](https://randomnerdtutorials.com/esp32-digital-inputs-outputs-arduino/) (Random Nerd Tutorials)
- Function reference: [Arduino language reference](https://docs.arduino.cc/language-reference/)

**For the why-questions** (read after you've built and experimented)

- Q1: [Light-Emitting Diodes](https://learn.sparkfun.com/tutorials/light-emitting-diodes-leds/all) (SparkFun), the section on current-limiting resistors
- Q2: [Pull-up Resistors](https://learn.sparkfun.com/tutorials/pull-up-resistors/all) (SparkFun)
- Q3: [Pulse Width Modulation](https://learn.sparkfun.com/tutorials/pulse-width-modulation/all) (SparkFun)
- Q4, only after you've described the problem yourself: [Debounce on a Pushbutton](https://docs.arduino.cc/built-in-examples/digital/Debounce/) (Arduino) and the [Wokwi pushbutton reference](https://docs.wokwi.com/parts/wokwi-pushbutton)

**For the crop model**

- [Crop Recommendation dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset) (Kaggle)
- [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html). Useful here: `value_counts`, `groupby(...).mean()`, `min`/`max`.

## Experiments (after it works)

- [ ] Remove the resistor and wire the LED straight to the pin.
- [ ] Change the button pin's mode and watch the serial output with nobody touching the button.
- [ ] Print the values passed to `analogWrite`. What range works? What happens at the extremes?

**What I saw:**

-

## What broke and how I fixed it

-

## Why-questions

**1. Why does the LED need a resistor, and what happens without one?**

My answer:

**2. Why does the button need a pull-up resistor, and what does a "floating" pin read?**

My answer:

**3. Why does PWM make an LED look dimmer when it's only ever fully on or off?**

My answer:

**4. (Stretch) Why did the toggle misbehave?**

My answer:

## Crop model task

- [ ] Download the dataset into `data/` (see `data/README.md`)
- [ ] Answer the questions in `model/week-01-explore.ipynb`

## Questions to bring to Claude

-
