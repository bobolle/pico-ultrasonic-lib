# pico-ultrasonic-lib

Example usage:
```
uss_init(TRIGGER_PIN, ECHO_PIN);

uint distance = get_pulse_cm(TRIGGER_PIN, ECHO_PIN, TIMEOUT);
printf("Distance from pulse in cm: %d\n", distance);

```
