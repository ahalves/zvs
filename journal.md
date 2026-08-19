---
title: "zvs"
github: "https://github.com/ahalves/zvs/"
description: "TPS2814-based ZVS Driver"
created_at: "2026-08-18"
---
# le journal
### 18 August - 1 hour 30 minutes total - finished schematic
<img width="763" height="301" alt="image" src="https://github.com/user-attachments/assets/59c0e9b0-ea3e-4965-ad8a-3df263e51b09" />

finished the schematic, found and assigned rating-crucial parts. it is a ZVS driver based around the TPS2814 MOSFET driver, which switches them rapidly keeping them out of their linear region. circuit adapted from u/McSlayR01, however upgraded to allow for more current, and higher voltage range (13-80V) input thanks to the buck converter (on the left of the image.)

### 19 August - 4 hours total - final schematic changes and finished pcb

<img width="657" height="278" alt="image" src="https://github.com/user-attachments/assets/3c570844-b5cb-42ba-a82e-4b040ef05871" />
<img width="592" height="814" alt="image" src="https://github.com/user-attachments/assets/bcb2e2ac-5317-4367-ada8-b198b7374562" />
<img width="856" height="948" alt="image" src="https://github.com/user-attachments/assets/bcd764bb-bc9f-427f-9832-db419eb656bb" />

edited the schematic to introduce a relay linked to a switch to allow for higher current operation. placed parts and routed pcb traces.

no model for inductors :(

### 19 August - 4.2 hours total - added heatsinks

<img width="216" height="302" alt="image" src="https://github.com/user-attachments/assets/c933e39d-2e58-4ee4-9f2e-4bdffb64cdb2" />

it has mosfet heatsinks now 👽



