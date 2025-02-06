# pico-ultrasonic-lib

## Features

- Get distance in cm from a pulse.
- Get duration in ms from a pulse.

## installation

- clone the repo to your project
- add it to your CMakeLists.txt

Example usage:
```
uss_init(TRIGGER_PIN, ECHO_PIN);

uint distance = get_pulse_cm(TRIGGER_PIN, ECHO_PIN, TIMEOUT);
printf("Distance from pulse in cm: %d\n", distance);

```
