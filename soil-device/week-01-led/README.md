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
