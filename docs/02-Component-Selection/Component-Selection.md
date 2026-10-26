---
title: Component Selection Example
---


| Solution    | Pros                                                                                                | Cons                                                                                                                                                 |
|-------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| DS18B20     | 1. Measures temperatures from −55°C to 125°C. 2. Digital output uses only one data pin.             | 1. Accuracy is ±0.5°C only within −10°C to 85°C. 2. Requires a pull-up resistor on the data line.                                                    |
| ZTP-148SRC1 | 1. Measures surface temperature without touching the object. 2. Fast response and high sensitivity. | 1. Requires additional circuitry to process its small output signal. 2. Measures surface temperature rather than directly measuring air temperature. |
| LMT86LPM    | 1. Low power consumption. 2. Analog output is easy to read with a microcontroller's ADC.            | 1. Requires an analog input pin. 2. Maximum specified accuracy is ±2.7°C.                                                                            |

| Solution                  | Pros                                                                                                                          | Cons                                                                                                                                |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| LS013B7DH03               | 1. Extremely low power consumption. 2. 128 × 128 resolution for displaying plant data.                                        | 1. Requires additional control signals beyond SPI. 2. Monochrome display with no color support.                                     |
| NHD-C12832A1Z-FSW-FBW-3V3 | 1. SPI interface simplifies communication with a microcontroller. 2. Built-in controller reduces processing requirements.     | 1. Low resolution of 128 × 32 pixels. 2. Requires a backlight to improve visibility in low-light conditions.                        |
| MDOB128064V2V-WI          | 1. OLED provides high contrast and does not require a separate backlight. 2. I²C interface uses only two communication lines. | 1. Small 0.96-inch screen limits the amount of information displayed. 2. White-only display cannot show color-coded plant statuses. |