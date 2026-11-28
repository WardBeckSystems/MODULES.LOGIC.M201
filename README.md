# M201 Relay Module · Logic

Ward-Beck Systems M201, 1979|12. Wiki page: [M201 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M201.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 24 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 14 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 101 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 31 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1979 - M201 - Relay Module.pdf](MANUALS/1979%20-%20M201%20-%20Relay%20Module.pdf) pages 5-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**H20 1 RELAY MODULE**

The H20I Relay Hodul e 1s designed t o be used as an audios wi tc her. It comprises two identical relay swi tc h1ng circuits, each capable of s w1tc hlng either one oft wo balanced inputs t o one balanced output.

Provision i s made for insertion of a fixed loss a tten lJa tor into the normally open path, expanding the use fulness o r the module for applicationS such as slating, par t-muting and similar functions.

The open circuit voltage a t mo dlJle pin 2 is a ppr oxi mat el y +9 volts. With the control terminal floating, the associated relay will bede energized. Alter native l y, a logic &quot; I&quot; voltages uppl ted to the control terminal. ranging from +9 t o +30 volts, willa lso keep the relay de -en erg 1zed. Once a logic &quot; 0&quot; i s a pp11ed tot Ile control input, ranging from 0 to +2 volts, the associated relay will energ 1ze. Separate, adjustable delays maybe selected fort her el ay pu l lin and d r op~ou t times. For adjustment of the delay times, refer t o the schematic.

A separate timing diagram on page 2-1 shows the operation of the logic circuitry.

Pins Band P oft he module co nneclor are each capable of sinking a current of approximately 20 mA maximum for such purposes a s external COntrol an d/or a n indicator lamp.

i -r

**H20 1 RELAY MODULE**

tII V - -- -.

Switch Input

**::-VSWIKM**

ur, pin 10

U4. pin 11

U2. pin 4

U4. pin 6

SII DOl..,,u~. &quot;&quot;&gt;..-0' -00' U2, pin 5 I:l I...•..,

U4. pin J I

U4, pin 8. u..., ~ N ('G l1 U

....... Df._[NIIGIIU

**INTEGRATED CIRCUIT DATA**

H Clll DUAL HONOSTA8LE HUlTI VI 8RATOR

The 74C2 21 dual ~onost~ble multivibr~t or Is a CMOS 1ntegra ted circuit. Each mult1v1b ra tor features a negat1ve-tran s itio n_ t r 1gge red input and a pos1t 1ve -transit10 n-triyyercd input either of which can be used as a n inhibit input, and a clear input. Once f1re d, the out put pulses are Independent o r further transitions oft he A and B Inputs and area function oft he oMtarnal timing co_ponc nt s CEXT ~n d REXT.

..,, ='iJ t-'!- •• ~ 1R/ C u 1

**1 CLR**

t-'!-1C u 1

2C u t -= &quot; l CLR

2R/ C U f -..:..

**IHP UTS OUTPUTS**

ClCAR A B Q Q, H • H19h level l • low lncl • 7 r ansi t ion fro_ low t o high l X X l H ~ • 7 r ~ n s lt f on fro_ h1 gh X H X l H t o low

l H

0 ne high level pulse

0 ne low tevet pulse

H ~ H ~ ~ X ~ I r re I uvan t

74CZl l

WAFlO ·BECK BYSTEMS LTO.

**HZOI R£LAY MOOULE**

PART O£ SCRI PTIO If MF&lt; MFS PART NUMBER C1 Capa d tor 0.1 uF IJS V (e_ et T3 9 0AI 04MOl SAS C2 • 10 uF /Z S Y • Tl9DC I06 MO ZSAS

C4 • 0.1 u Fn S V • T3 9 0A 10 4 M0 3 5AS C5 • 10 u F/ Z5 Y • T390C I06 M0 2 5AS

C7 • I u FIJ S V • T39 0B1 0 5MO l SAS C8 • 4.7 u r /Z s V • T3 9DC4 7 SM0 2 5 AS

COl Diode Motorola I N40 0 3 CO2 • Fa1 r c h ll d I N4 14 8

CR4 • Motorola I N40 0 l COS • Fair child I N4 14 8

CR7 • Motorola I N4 0 0 l

Relay

YZl030-A202 1-A to 4

Ql 'r r a ns t s tor National 2&quot;3569

Resistor \ W 51

Ph lllps

R4 Trim pot Pi her PT l Oh (2.5) • R5 Resistor ~ W 5% Phi l1ps •

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHpkY1lTY0lQNjg/view?resourcekey=0-oPrOQqmScDbcqbQZoeoePw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHpkY1lTY0lQNjg&resourcekey=0-oPrOQqmScDbcqbQZoeoePw" width="240" alt="1979 - M201 - 201-02-001 - SEC SHORT SHORT OPEN SHORT OPEN OPEN.jpg"></a><br><sub>1979|12 · 201-02-001 - SEC SHORT SHORT OPEN SHORT OPEN OPEN · <a href="SCHEMATICS/1979%20-%20M201%20-%20201-02-001%20-%20SEC%20SHORT%20SHORT%20OPEN%20SHORT%20OPEN%20OPEN%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHlkdlNKZFdSR0k/view?resourcekey=0-7YJyL_4OMYBV7cCOJTBgxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHlkdlNKZFdSR0k&resourcekey=0-7YJyL_4OMYBV7cCOJTBgxQ" width="240" alt="1979 - M201 - 201-06-001 - CKO RIL RELAY MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1979|12 · 201-06-001 - CKO RIL RELAY MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1979%20-%20M201%20-%20201-06-001%20-%20CKO%20RIL%20RELAY%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSThIeURyaGZWVkk/view?resourcekey=0-DCfF1riNcx3aIdov_rtF_w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSThIeURyaGZWVkk&resourcekey=0-DCfF1riNcx3aIdov_rtF_w" width="240" alt="1979 - M201 - 201-06-001 - RELAY MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1979|12 · 201-06-001 - RELAY MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1979%20-%20M201%20-%20201-06-001%20-%20RELAY%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnVTVDRySHVxbHc/view?resourcekey=0-SA2EtrC1RBp9bGUu_zsqcQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnVTVDRySHVxbHc&resourcekey=0-SA2EtrC1RBp9bGUu_zsqcQ" width="240" alt="1979 - M201 - 201-02-001 - DELAY STRAPPING DELAY NUMPER NUMPER.jpg"></a><br><sub>1979|12 · 201-02-001 - DELAY STRAPPING DELAY NUMPER NUMPER · <a href="PINOUTS/1979%20-%20M201%20-%20201-02-001%20-%20DELAY%20STRAPPING%20DELAY%20NUMPER%20NUMPER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS1VHWEh0QkFyYms/view?resourcekey=0-BFjGKm52jWr8bfCjnxqdCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS1VHWEh0QkFyYms&resourcekey=0-BFjGKm52jWr8bfCjnxqdCA" width="240" alt="1979 - M201 - P13 - Pin outs.jpg"></a><br><sub>1979|12 · P13 - Pin outs · <a href="PINOUTS/1979%20-%20M201%20-%20P13%20-%20Pin%20outs%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

Read from 2 pinout pictures (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +24 V | power |  | high |
| 2 | DC CONTROL 1 IN | control_in | DC CONTROL 1 IN | high |
| 3 | N/C | nc |  | high |
| 4 | ENERGIZED INPUT 1 | in | ENERGIZED INPUT 1 | high |
| 5 | OFF INPUT 1 | in | OFF INPUT 1 | high |
| 6 | SHIELD | shield | shield | high |
| 7 | OUTPUT 1 | out | OUTPUT 1 | high |
| 8 | N/C | nc |  | high |
| 9 | OUTPUT 2 | out | OUTPUT 2 | high |
| 10 | N/C | nc |  | high |
| 11 | OFF INPUT 2 | in | OFF INPUT 2 | high |
| 12 | ENERGIZED INPUT 2 | in | ENERGIZED INPUT 2 | high |
| 13 | DC CONTROL 2 IN | control_in | DC CONTROL 2 IN | high |
| 14 | CONTROL COMMON | ground |  | high |
| 15 | N/C | nc |  | high |
| A | N/C | nc |  | high |
| B | DC CONTROL 1 OUT | control_out | DC CONTROL 1 OUT | high |
| C | N/C | nc |  | high |
| D | ENERGIZED INPUT 1 | in | ENERGIZED INPUT 1 | high |
| E | OFF INPUT 1 | in | OFF INPUT 1 | high |
| F | N/C | nc |  | high |
| H | OUTPUT 1 | out | OUTPUT 1 | high |
| J | N/C | nc |  | high |
| K | OUTPUT 2 | out | OUTPUT 2 | high |
| L | SHIELD | shield | shield | high |
| M | OFF INPUT 2 | in | OFF INPUT 2 | high |
| N | ENERGIZED INPUT 2 | in | ENERGIZED INPUT 2 | high |
| P | DC CONTROL 2 OUT | control_out | DC CONTROL 2 OUT | high |
| R | N/C | nc |  | high |
| S | N/C | nc |  | high |

**Straps:** PULL-IN DELAY 1: J5-A J5-B · DROP-OUT DELAY 1: J6-A J6-B · PULL-IN DELAY 2: J7-A J7-B · DROP-OUT DELAY 2: J8-A J8-B · VARIATION J1-J4: J1 J2 J3 J4

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0RnLWZ6eUxuT1k/view?resourcekey=0-L4sXHQHItjXYZ669j1LKrw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0RnLWZ6eUxuT1k&resourcekey=0-L4sXHQHItjXYZ669j1LKrw" width="240" alt="1979 - M201 - P01 - Cover.jpg"></a><br><sub>1979|12 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZVFULXhSR3hHZEU/view?resourcekey=0-oln7XB-Je1S5Gf4SmrZ94g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZVFULXhSR3hHZEU&resourcekey=0-oln7XB-Je1S5Gf4SmrZ94g" width="240" alt="1979 - M201 - P02.jpg"></a><br><sub>1979|12 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa3FURjNmNEdjRjg/view?resourcekey=0-hkhFhMMXkPcMa6DBMEXmaw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa3FURjNmNEdjRjg&resourcekey=0-hkhFhMMXkPcMa6DBMEXmaw" width="240" alt="1979 - M201 - P03.jpg"></a><br><sub>1979|12 · P03</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2pFTzNRTW02cGc/view?resourcekey=0-sY159OFQp4XE1lQfzRAXxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2pFTzNRTW02cGc&resourcekey=0-sY159OFQp4XE1lQfzRAXxQ" width="240" alt="1979 - M201 - P04 - Warranty.jpg"></a><br><sub>1979|12 · P04 - Warranty</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkE0UU54cGNwc2c/view?resourcekey=0-tBqb0BuX019WLZ7IvO4X4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkE0UU54cGNwc2c&resourcekey=0-tBqb0BuX019WLZ7IvO4X4Q" width="240" alt="1979 - M201 - P05 - 1-1.jpg"></a><br><sub>1979|12 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWMwUXdOSElWcDA/view?resourcekey=0-LzUoDZNkrcKSFXq1XMqu3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWMwUXdOSElWcDA&resourcekey=0-LzUoDZNkrcKSFXq1XMqu3w" width="240" alt="1979 - M201 - P06 - 2-1.jpg"></a><br><sub>1979|12 · P06 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV2hUNE92X2phMGs/view?resourcekey=0-BgIl8P_ES93gjb8eaWmqJw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV2hUNE92X2phMGs&resourcekey=0-BgIl8P_ES93gjb8eaWmqJw" width="240" alt="1979 - M201 - P07 - 74C221.jpg"></a><br><sub>1979|12 · P07 - 74C221</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWGxwUWJFdjBYYVE/view?resourcekey=0-Uu-iprsbKoAsVcLvpGXqLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWGxwUWJFdjBYYVE&resourcekey=0-Uu-iprsbKoAsVcLvpGXqLA" width="240" alt="1979 - M201 - P08 - 4-1.jpg"></a><br><sub>1979|12 · P08 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSkVNSWk1WnBYWFE/view?resourcekey=0-kfGf4DeK6reZkORqZtnZaQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSkVNSWk1WnBYWFE&resourcekey=0-kfGf4DeK6reZkORqZtnZaQ" width="240" alt="1979 - M201 - P09 - 4-2.jpg"></a><br><sub>1979|12 · P09 - 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3NvQTZJQ0xTMWM/view?resourcekey=0-msCjzj6y8H7Vlb8d2oqgKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3NvQTZJQ0xTMWM&resourcekey=0-msCjzj6y8H7Vlb8d2oqgKQ" width="240" alt="1979 - M201 - P10 - 4-3.jpg"></a><br><sub>1979|12 · P10 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdXhEVzJqdWIxTkE/view?resourcekey=0-LMqWx3XAka4r2GZRsxfizw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdXhEVzJqdWIxTkE&resourcekey=0-LMqWx3XAka4r2GZRsxfizw" width="240" alt="1979 - M201 - Relay Module (2).pdf"></a><br><sub>1979|12 · Relay Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGp0bWFOWVNic1U/view?resourcekey=0-IW4Hrs1w_AdK-AvfMjdiOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGp0bWFOWVNic1U&resourcekey=0-IW4Hrs1w_AdK-AvfMjdiOw" width="240" alt="1979 - M201 - Relay Module.pdf"></a><br><sub>1979|12 · Relay Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRjBSb2RISDg1Tjg/view?resourcekey=0-7ZK9B4hoYyiDMvTlr4COPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRjBSb2RISDg1Tjg&resourcekey=0-7ZK9B4hoYyiDMvTlr4COPw" width="240" alt="1979 - M201 - WBS test procedures 1.jpeg"></a><br><sub>1979|12 · WBS test procedures 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSlMyNVJ3LW5OX2s/view?resourcekey=0-7q77C26tk6YDsEL5MWZMaQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSlMyNVJ3LW5OX2s&resourcekey=0-7q77C26tk6YDsEL5MWZMaQ" width="240" alt="1979 - M201 - WBS test procedures 2.jpeg"></a><br><sub>1979|12 · WBS test procedures 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ1RhVUhyMG9VV3c/view?resourcekey=0-sw1JRdSi1eJUhUaxTTaQFw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ1RhVUhyMG9VV3c&resourcekey=0-sw1JRdSi1eJUhUaxTTaQFw" width="240" alt="1979 - M201 - WBS test procedures.jpeg"></a><br><sub>1979|12 · WBS test procedures</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWpVeHVDeHM3bkU/view?resourcekey=0-bUkpdmFqQlSLALCjLTAKGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWpVeHVDeHM3bkU&resourcekey=0-bUkpdmFqQlSLALCjLTAKGw" width="240" alt="1979 - M201 - p1.jpg"></a><br><sub>1979|12 · p1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTmltU2VoaUEyTGc/view?resourcekey=0-RL20cSCiXTj7kfLB0itOXA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTmltU2VoaUEyTGc&resourcekey=0-RL20cSCiXTj7kfLB0itOXA" width="240" alt="1979 - M201 - p2.jpg"></a><br><sub>1979|12 · p2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOWZ4T2NRWlpVMnc/view?resourcekey=0-0MxYLgPPL0d0BMQUp1Mu6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOWZ4T2NRWlpVMnc&resourcekey=0-0MxYLgPPL0d0BMQUp1Mu6w" width="240" alt="1979 - M201 - p3.jpg"></a><br><sub>1979|12 · p3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVzMzaVBZSzFueEE/view?resourcekey=0-FikTRulrIJlmGKGVyfh5VA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVzMzaVBZSzFueEE&resourcekey=0-FikTRulrIJlmGKGVyfh5VA" width="240" alt="1979 - M201 - p4.jpg"></a><br><sub>1979|12 · p4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVTJfY2hRR2lyWGc/view?resourcekey=0-383Qkm2si9L6Vs1z4ccBCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVTJfY2hRR2lyWGc&resourcekey=0-383Qkm2si9L6Vs1z4ccBCw" width="240" alt="1979 - M201 - p5.jpg"></a><br><sub>1979|12 · p5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVdPcndaX0d3QUU/view?resourcekey=0-A7QV05HfCNz_0WRV3v6SOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVdPcndaX0d3QUU&resourcekey=0-A7QV05HfCNz_0WRV3v6SOA" width="240" alt="1979 - M201 - p6.jpg"></a><br><sub>1979|12 · p6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVNwZXQtU0hHQmc/view?resourcekey=0-DxTsb3deJhSupRM-nbhMUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVNwZXQtU0hHQmc&resourcekey=0-DxTsb3deJhSupRM-nbhMUg" width="240" alt="1979 - M201 - p7.jpg"></a><br><sub>1979|12 · p7</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1979 - M201 - 201-02-001 - DELAY STRAPPING DELAY NUMPER NUMPER.kicad_sch](KICAD/1979%20-%20M201%20-%20201-02-001%20-%20DELAY%20STRAPPING%20DELAY%20NUMPER%20NUMPER.kicad_sch)
- [1979 - M201 - 201-02-001 - SEC SHORT SHORT OPEN SHORT OPEN OPEN.kicad_sch](KICAD/1979%20-%20M201%20-%20201-02-001%20-%20SEC%20SHORT%20SHORT%20OPEN%20SHORT%20OPEN%20OPEN.kicad_sch)
- [19xx - M201 - Integrated Circuit Data 74C221 Dual Monostable Multivibrator.kicad_sch](KICAD/19xx%20-%20M201%20-%20Integrated%20Circuit%20Data%2074C221%20Dual%20Monostable%20Multivibrator.kicad_sch)
- [M201.kicad_sym](KICAD/M201.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
