# Bill of Materials

In this folder you will find the BOM for the PSU, in various formats: CSV, Excel and OpenDocument Spreadsheet. Below in markdown format:



| Ref Desc | Quantity | Manufacturer | Manufacturer Part Number | Description | Package | Type | Comment |
| -------- | -------- | ------------ | ------------------------ | ----------- | ------- | ---- | ------- |
| C1 | 1 | Yageo | CC0603KRX7R9BB104 | 0.1µF ±10% 50V MLCC X7R 0603 | 0603 | SMD |  |
| C2, C3, C4, C5 | 4 | Taiyo Yuden | EMK325BJ476MM-T | 47µF ±20% 16V MLCC X5R 1210 | 1210 | SMD | Use 25V if you can to increase VIN range |
| C6, C7 | 2 | TDK | C3216X7T2E224K160AA | 0.22µF ±10% 250V MLCC X7T 1206 | 1206 | SMD | Must be 250V+ rated |
| C8 | 1 | Yageo | AC0603KRX7R9BB103 | 0.01µF ±10% 50V MLCC X7R 0603 | 0603 | SMD |  |
| C9 | 1 | Yageo | CC0603KRX7R9BB223 | 0.022µF ±10% 50V MLCC X7R 0603 | 0603 | SMD |  |
| C10 | 1 | Yageo | CC0603KRX7R9BB101 | 100pF ±10% 50V MLCC X7R 0603 | 0603 | SMD |  |
| C11 | 1 | Yageo | CC0603MRX5R7BB106 | 10µF ±20% 16V MLCC X5R 0603 | 0603 | SMD |  |
| D1 | 1 | ROHM | RFN1LAM6STR | Diodes - General Purpose, Power, Switching 600V VR 0.8A IO SOD-128; PMDTM | SOD128 | SMD | ES1G works well if you'd like a more commonly available part |
| L1 | 1 | Coilcraft | DA2032-ALB | Flyback Transformer 1:10 10uH | DA2032 | SMD |  |
| M1 | 1 | Infineon | IRLR3110ZTRPBF | HEXFET N-CH 100V 42A DPAK TO-252-3 | TO-252-3 | SMD | Any fast switching MOSFET works but this one is particularly good |
| R1, R8 | 2 | Yageo | RC0603FR-07140KL | Resistor SMD 140K 1% 1/10W 0603 | 0603 | SMD |  |
| R2 | 1 | Yageo | MCR18EZPD1004 | Resistor SMD 1M 0.5% 1/8W 1206 | 1206 | SMD |  |
| R3, R6 | 2 | Yageo | RC0603FR-0710KL | Resistor SMD 10K 1% 1/10W 0603 | 0603 | SMD |  |
| R4 | 1 | Yageo | PE1206FRF470R02L | Resistor Current Sense SMD 0.02R 1% 1W 1206 | 1206 | SMD | Current limiting resistor 0.02 1W is a must for stability |
| R5 | 1 | Yageo | RC0603FR-0722RL | Resistor SMD 22R 1% 1/10W 0603 | 0603 | SMD |  |
| R7 | 1 | Yageo | RC0603FR-0763K4L | Resistor SMD 63.4K 1% 1/10W 0603 | 0603 | SMD | 59K-66K5 works well. |
| U1 | 1 | Linear | LT3757EMSE#PBF | LT3757 Switching Voltage Regulators Boost, Fly, SEPIC & Inv Cntr | MSOP10 | SMD | Any LT3757 or LT3757A variants in MSOP10 will work |
