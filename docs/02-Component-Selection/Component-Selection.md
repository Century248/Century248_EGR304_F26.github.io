---
title: Component Selection Example
---

### Temperature Sensor

1. DS18B20

| Pros | Cons |
|---|---|
| 1. Digital output (easy MCU connection). | 1. Requires 1-Wire communication. |
| 2. ±0.5°C accuracy. | 2. Slower temperature conversion. |
| 3. Waterproof probe options available. | 3. Requires pull-up resistor. |

2. ZTP-148SRC1

| Pros | Cons |
|---|---|
| 1. Non-contact temperature measurement. | 1. Requires additional signal processing. |
| 2. Fast response time. | 2. More difficult to calibrate. |
| 3. Includes ambient temperature compensation. | 3. Measures surface temperature, not air temperature. |

3. LMT86LPM

| Pros | Cons |
|---|---|
| 1. High accuracy (±0.4°C typical). | 1. Requires an analog MCU input. |
| 2. Very low power consumption. | 2. Requires temperature conversion calculations. |
| 3. Simple analog output. | 3. Sensitive to electrical noise. |

### Display

1. LS013B7DH03

| Pros | Cons |
|---|---|
| 1. Extremely low power consumption. | 1. Monochrome display. |
| 2. 128 × 128 resolution. | 2. Requires specialized FPC connection. |
| 3. Good outdoor visibility. | 3. Limited visibility in darkness without backlighting. |
 
2. NHD-C12832A1Z-FSW-FBW-3V3

| Pros | Cons |
|---|---|
| 1. Low power consumption. | 1. Limited 128 × 32 resolution. |
| 2. SPI communication. | 2. Small viewing area. |
| 3. Transflective screen for visibility in different lighting. | 3. Requires external backlight power. |

3. MDOB128064V2V-WI

| Pros | Cons |
|---|---|
| 1. High contrast OLED display. | 1. Higher power consumption than memory LCD. |
| 2. 128 × 64 resolution. | 2. Potential OLED burn-in. |
| 3. Simple I2C communication. | 3. More expensive than basic LCD displays. |

### Power Regulation

1. L7805ABV-DG

| Pros | Cons |
|---|---|
| 1. Fixed 5V output. | 1. Generates excess heat. |
| 2. Up to 1.5A output current. | 2. Lower power efficiency. |
| 3. Built-in thermal protection. | 3. Requires heat management at higher loads. |

2. NJM7805FA

| Pros | Cons |
|---|---|
| 1. Stable 5V output. | 1. Generates excess heat. |
| 2. Up to 1.5A output current. | 2. Lower power efficiency. |
| 3. Built-in short-circuit protection. | 3. Requires higher input voltage than output. |

3. MIC5156-3.3BN

| Pros | Cons |
|---|---|
| 1. Provides 3.3V regulation. | 1. Requires an external MOSFET. |
| 2. Low standby current. | 2. More complicated circuit design. |
| 3. Adjustable output and enable control options. | 3. Requires additional external components. |

### Power

1. 36-2477-ND Battery Holder + E91VP AA Batteries

| Pros | Cons |
|---|---|
| 1. Portable power source. | 1. Batteries eventually need replacing. |
| 2. Easy battery replacement. | 2. Limited operating time. |
| 3. No wall outlet required. | 3. Output voltage decreases as batteries discharge. |

2. WSU090-1300-R

| Pros | Cons |
|---|---|
| 1. Provides regulated 9V DC output. | 1. Requires a wall outlet. |
| 2. Supplies up to 1.3A. | 2. Not portable without additional power. |
| 3. Supports 100–240V AC input. | 3. Requires a compatible barrel jack. |

3. P124 1.2W Solar Panel

| Pros | Cons |
|---|---|
| 1. Provides renewable power. | 1. Dependent on sunlight. |
| 2. Compact outdoor design. | 2. Requires charging circuitry. |
| 3. 6V output with 200mA current. | 3. Requires battery storage. |