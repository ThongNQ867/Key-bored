# Key-bored
This is a split keyboard that uses XIAO nRF52840 and MX switches with hotswap, LED and 3-D printed case.

This project is a Split wireless keyboard that run on 2 Xiao nRF52840 on each side. This keyboard runs on ZMM firmware and used MX switches. I made this project because split keyboards are very expensive and I think making one will help people have the similar experience with relatively lower price. Also, the parts like Xiao are reuseable for many projects, making it really cost effective. 

How to use:
- After print the PCBA from JLC PCB or order the parts and hand soldered them, solder the hotswap sockets, Xiao, JST pins into the pcb, and finally attach the swithces into the socket.
- Wire the Xiao with your computer and flash each of them with the firmware
Basicaly we got a working keyboard now.
- For the case, put the heat inserts in, lay the pcb on top and screw it with M3 (3mm) screws.

The assembled design should look like this

![alt text](image/image.png)

The PCB design:

![alt text](image/image-1.png)
![alt text](image/image-6.png)

Schematic (each side):

![alt text](image/image-2.png)
![alt text](image/image-3.png)
![alt text](image/image-4.png)
![alt text](image/image-5.png)


BOM:

## Bill of Materials (BOM)

| Name                         | Comment              | Footprint                              | JLCPCB Part #                  | Quantity | Links                                                                 | Price (Not include shipping) |
|------------------------------|----------------------|----------------------------------------|---------------------------------|----------|------------------------------------------------------------------------|-------------------------------|
| CR0805F88063G                | 806k                 | R_0805_2012Metric                      | C101872                        | 4        | https://jlcpcb.com/partdetail/LIZElec-CR0805F88063G/C101872           | Within PCB                    |
| 1N4148W diode                | 1N4148W              | D_SOD-123                              | C81598                         | 46       | https://jlcpcb.com/partdetail/ST_Semtech-1N4148W/C81598               | Within PCB                    |
|                              |                      | TestPoint_Pad_D2.0mm                   |                                 | 4        |                                                                        | Within PCB                    |
| PCB from JLCPCB              |                      |                                        |                                 | 1        |                                                                        | 35.71                         |
| Kalih hotswap sockets        |                      | SW_MX_HS_CPG151101S11_1u               | Not from JLC PCB               | 46       | https://www.aliexpress.us/item/3256809253442692.html                  | 12.17                         |
| XIAO nRF52840 SMD            |                      | modified-XIAO-nRF52840-SMD             | Not from JLC PCB               | 2        | https://www.aliexpress.us/item/3256806802639384.html                  | 17.96                         |
| SK6812MINI - E               | SK6812               | MX_SK6812MINI-E_REV                    | Hand solder, not from JLC PCB  | 46       | https://www.aliexpress.us/item/3256805061849599.html                  | 6.16                          |
| JST connector                |                      | JST_PH_S2B-PH-K_1x02_P2.00mm_Horizontal| Not from JLC PCB               | 2        | https://www.aliexpress.us/item/3256804769340392.html                  | 1.60                          |
| MX switches                  |                      |                                        | Not from JLC PCB               | 46       | https://www.aliexpress.us/item/3256805881801670.html                  | 8.05                          |
| Rechargeable LiPo battery    | 3.7V 100mAh          |                                        | Not from JLC PCB               | 2        | https://www.aliexpress.us/item/3256805604531299.html                  | 7.01                          |
| Heat inserts                 | M3x5x4               |                                        | Not from JLC PCB               |    10      | https://www.aliexpress.us/p/shoppingcart/index.html                   | 2.63                          |
