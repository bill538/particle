# IOT_Smart_Switch
This project is a IOT Smart Switch leveraging the Particle Photon.


![Circuit Diagram - IOT_Smart_Switch](https://github.com/bill538/IOT_Smart_Switch/blob/master/IOT_Smart_Switch.png)

TidyCad files: 
  [IOT_Smart_Switch](https://github.com/bill538/IOT_Smart_Switch/blob/master/IOT_Smart_Switch.dsn)
  [Custom Symbol](https://github.com/bill538/IOT_Smart_Switch/blob/master/particle.TCLib)



# Mappings
Pin     | Pin Variable   | State Variable | Previous State Variable
------- | -------------- | -------------- | ----------------------- 
D0 | ic2_sda
D1 | i2c_scl
D2 | RelayIn1 | RelayIn1_State |
D3 | RelayIn2 | RelayIn2_State |
D4 | RelayIn3 | RelayIn3_State |
D5 | RelayIn4 | RelayIn4_State |
A2 | Switch1 | Switch1_State | Prev_Switch1_State
A3 | Switch2 | Switch2_State | Prev_Switch2_State
A4 | Switch3 | Switch3_State | Prev_Switch3_State
A5 | Switch4 | Switch4_State | Prev_Switch4_State
  
# Hardware
Description     | Model #         | Quanity | Price | Shipping | Total 
--------------- | --------------- | ------- | ---- | -------- | -----
[CARLON 8" x 8" x 4" Junction Box](http://www.lowes.com/ProductDisplay?productId=3260229) | E989N-CAR | 1 | $22.64 | $0.00 | $22.64 |
[Particle Photon with headers](https://store.particle.io/collections/photon) | | 1 | $19.00 |  | $19.00
[Grove - LCD RGB Backlight](http://www.seeedstudio.com/depot/Grove-LCD-RGB-Backlight-p-1643.html) | 104030001 | 1 | $13.90 | | $13.90
[100pcs Brass M3*15mm Hex Column Standoff Support](http://www.ebay.com/itm/161863006976) | 161863006976 | 1 | $6.29 | $1.99 | $8.28
[10A AMP PANEL MOUNT THERMAL BREAKER](http://www.ebay.com/itm/172007409375) | | 1 | $4.75 | $2.45 | $7.20 |
[5V 4 Channel PLC Relay Module Controller F Arduino Mega2560 UNO R3 Raspberry Pi](http://www.ebay.com/itm/331591955325) | | 1 | $4.15 | $1.50 | $5.65 
[Leviton 15 Amp Single-Pole Switch - White (10-Pack)](http://www.homedepot.com/p/Leviton-15-Amp-Single-Pole-Switch-White-10-Pack-M24-01451-2WM/100075329) | M24-01451-2WM | 1 | $4.90 | $0.00 | $4.90
[15 Amp Duplex Outlet - White (10-Pack)](http://www.homedepot.com/p/Leviton-15-Amp-Duplex-Outlet-White-10-Pack-M24-05320-WMP/100055784) | M24-05320-WMP | 1 | $4.90 | $0.00 | $4.90
[50 pcs M3 Male x M3 Female Screw PCB Stand-off Spacer Hex 26mm Length](http://www.newegg.com/Product/Product.aspx?Item=9SIA67038S9220) | 9SIA67038S9220 | 1 | $4.42 | $0.00 | $4.42
[100pcs Stainless steel M3*6mm Screw](http://www.ebay.com/itm/161863006976) | 161863006976 | 1 | $3.59 | $0.00 | $3.59
[200pcs 10k Ohm 10,000r 1/6w=1/8w Metal Film Resistors 0.125watt 1%](http://www.ebay.com/itm/like/301642249557?ul_noapp=true&chn=ps&lpid=82) | | 1 | $3.45 | $0.00 | $3.45
[50 Pcs M3 Male x M3 Female Hex Head PCB Standoffs Spacers 12mm Length](http://www.newegg.com/Product/Product.aspx?Item=9SIA67038S9276) | 9SIA67038S9276 | 1 | $1.83 | $0.00 | $1.83
[US Plug 2A Wall AC DC Adapter + Micro USB Charger Cable](http://www.ebay.com/itm/like/281761499068?ul_noapp=true&chn=ps&lpid=82) | | 1 | $1.65 | $0.00 | $1.65 
[DIY Breadboard 270 Point Position Solderless PCB Bread Board 23x12 SYB-46 Test](http://www.ebay.com/itm/191547516665) | 191547516665 | 1 | $1.47 | $0.00 | $1.47
[Hot Sale! 40 Pcs Colorful 1 Pin Male to Female Jumper Cable Wires 20cm Long](http://www.newegg.com/Product/Product.aspx?Item=9SIA67038S9135) | 9SIA67038S9135 | 1 |$1.17 | $0.00 | $1.17
[20cm Long F/F Solderless Flexible Breadboard Jumper Cable Wire 40 Pcs](http://www.newegg.com/Product/Product.aspx?Item=9SIA67038W2538) | 9SIA67038W2538 | 1 | $1.11 | $0.00 | $1.11
# Grand Total: $105.16
