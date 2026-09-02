

![Eye tracking camera](https://github.com/user-attachments/assets/1eb9cfd6-ad58-4493-b880-12d4a0ee1269)

## Bill of materials

| Component | Quantity | Notes / Specifications |
| :--- | :---: | :--- |
| [PCB](https://jlcpcb.com/) | 1 | PCB thickness 0.4 - 0.6 mm |
| [Camera](https://www.aliexpress.com/item/32824666630.html?spm=a2g0o.order_list.order_list_main.4.20661802AZe992) | 1 | — |
| [SIL Connectors](https://cpc.farnell.com/harwin/d01-9972042/socket-sil-20way/dp/CN25209?mckv=sshopping_dc) | 2 | — |
| [Resistors](https://uk.rs-online.com/web/p/surface-mount-resistors/2413233?searchId=43439db6-fc9c-4466-bd31-436fe6f9f2b1&gb=s) | 3 | — |
| [IR LED](https://uk.rs-online.com/web/p/ir-leds/1847276?gb=s) | 3 | — |

## Assembly instructions

- Hold the PCB using tape on the thinner side
- Solder the IR LEDs in the following orientation (Polarity)
<img width="1461" height="1219" alt="607056966-f32358ff-5b07-4499-b614-00222abcf55b" src="https://github.com/user-attachments/assets/58972f6c-e026-42e3-ae1e-465e12de9c26" />

- Solder the resistors in the opposite side
<img width="467" height="311" alt="image" src="https://github.com/user-attachments/assets/12d1075e-e86a-40e1-a069-245700331edd" />



- Solder the SIL connector
<img width="1313" height="411" alt="image" src="https://github.com/user-attachments/assets/f8ac782d-6a88-4e94-b6df-bd8474c21a04" />

- Remove the SIL connector plastic part with clippers and cut the top excess of the SIL connector
<img width="544" height="370" alt="image" src="https://github.com/user-attachments/assets/61495541-a102-468c-ae29-70b8b0139fef" />


- Strip off the camera cables
<img width="793" height="362" alt="image" src="https://github.com/user-attachments/assets/a5d4e596-79af-4ee5-923b-235b6551356a" />

- Solder the camera wires with each corresponding pad and glue the camera with the PCB using super glue
<img width="556" height="317" alt="image" src="https://github.com/user-attachments/assets/8346bf6b-5053-4dd2-8575-b1a9810395eb" />

- Solder the Vcc (3-3.3V), GND, and signal terminals with the cables

## Some notes

- The mass of the frame with the SIL conenctors is approximately 90 mg.
<img width="1020" height="765" alt="image" src="https://github.com/user-attachments/assets/d6919958-8e0c-4ee9-9ebd-a95f9d995a3e" />

- In a second design iteration we added one degree of freedom to the 3D desing to allow for the camera orientation
<img width="1341" height="583" alt="image" src="https://github.com/user-attachments/assets/35369488-14d3-4294-9aed-ff50649e5a61" />

