# Encoder-AS5600
Arduino lib for controll AS5600
        Connect 
Arduino        AS5600
  VCC           3.3V (or 5V, but 1microF to GND)
  GND           GND
  SCL           SCL
  SDA           SDA
  DIR           GND CLOCKWISE increase (or 5V, 3.3V COUNTER CLOCKWISE increase)

In Arduino code
#include <Wire.h>

ENCODER name;
void setup()
{
  Wire.begin();
}
