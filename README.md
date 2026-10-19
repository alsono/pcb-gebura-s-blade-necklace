i'm rewriting this because github genuinely vaporized my last one  (i'm sick this is the best writing i can manage i swear i'll rewrite all of this) <br>
# intro 
just a pcb with togglable lights (via button) that uses a 555 timer and like vibrates <br>
heres the circuit <br>
![schema](https://github.com/alsono/pcb-gebura-s-blade-necklace/blob/main/resources/schematic.png)<br>
and heres the pcb <br>
![pcb](https://github.com/alsono/pcb-gebura-s-blade-necklace/blob/main/resources/pcb.png)<br>
and a 3d render of it <br>
![pcb3d](https://github.com/alsono/pcb-gebura-s-blade-necklace/blob/main/resources/pcb3d.png)<br>
heres what it looks like when in jlc pcb in both red and black <br>
![pcbord](https://github.com/alsono/pcb-gebura-s-blade-necklace/blob/main/resources/orderblack.png) <br>
![pcbord](https://github.com/alsono/pcb-gebura-s-blade-necklace/blob/main/resources/pcborderred.png) <br>
bill of materials for what you'll need (all comes in the solder kit from the hack club event [solder](https://solder.hackclub.com/))
|Reference     |Qty|Value       |DNP|Exclude from BOM|Exclude from Board|Footprint                                                  |Datasheet                                                                 |
|--------------|---|------------|---|----------------|------------------|-----------------------------------------------------------|--------------------------------------------------------------------------|
|BT1,BT2       |2  |Battery_Cell|   |                |                  |Battery:BatteryHolder_Keystone_3034_1x20mm                 |                                                                          |
|C1            |1  |C           |   |                |                  |Capacitor_THT:CP_Axial_L10.0mm_D4.5mm_P15.00mm_Horizontal  |                                                                          |
|D1,D2,D3,D4,D5|5  |LED         |   |                |                  |LED_THT:LED_D5.0mm_Horizontal_O1.27mm_Z3.0mm               |                                                                          |
|M1            |1  |Motor_DC    |   |                |                  |Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P2.54mm_Vertical|                                                                          |
|Q1            |1  |2N3904      |   |                |                  |Package_TO_SOT_THT:TO-92_Inline                            |https://www.onsemi.com/pub/Collateral/2N3903-D.PDF                        |
|R1,R2,R4      |3  |4.7k        |   |                |                  |Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P2.54mm_Vertical|                                                                          |
|R3            |1  |47k         |   |                |                  |Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P2.54mm_Vertical|                                                                          |
|SW2           |1  |SW_Push     |   |                |                  |Button_Switch_THT:KSA_Tactile_SPST                         |                                                                          |
|U2            |1  |ICM7555xP   |   |                |                  |Package_DIP:DIP-8_W7.62mm                                  |http://www.intersil.com/content/dam/Intersil/documents/icm7/icm7555-56.pdf|
