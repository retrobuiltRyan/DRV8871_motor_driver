# DRV8871_motor_driver
PCB for DRV8871: a basic DC motor driver for small  to maybe medium brushed motors. https://www.ti.com/lit/ds/symlink/drv8871.pdf

### Quick Specs
- H-Bridge Motor Driver  
- Drives one DC motor, one winding of a stepper motor, or other loads  
- Wide operating voltage: **6.5 V to 45 V**  
- **565 mΩ** typical RDS(on) (HS + LS)  
- **3.6 A** peak current drive  
- PWM control interface  
- Current regulation without a sense resistor  

<img width="1913" height="1002" alt="drv8871_kicad" src="https://github.com/user-attachments/assets/3d3ff92a-5039-4fc2-9cda-1258705aab64" />

##BoM
### Bill of Materials (BOM)

| Reference | Value      | Qty | Digi-Key P/N                 |
|-----------|------------|-----|------------------------------|
| C1        | 47µF 35V   | 1   | PCE5014CT-ND                 |
| C2        | 0.1µF 35V  | 1   | 399-C1206C104M6RACTUCT-ND    |
| D2        | LED        | 1   | 732-4989-1-ND                |
| D3, D4    | SMF15A     | 2   | SMF15A-E3-08CT-ND            |
| R1        | 32k        | 1   | 2019-RN73H2BTTD3202F100CT-ND |
| R3        | 1k         | 1   | 311-1.00KFRCT-ND             |
| U1        | DRV8871DDA | 1   | 296-43024-1-ND               |

