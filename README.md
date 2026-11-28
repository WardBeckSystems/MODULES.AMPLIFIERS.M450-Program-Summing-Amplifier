# M450 Program Summing Amplifier · Amplifiers

Ward-Beck Systems M450, 1974|7. Wiki page: [M450 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.AMPLIFIERS.M450-Program-Summing-Amplifier/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 36 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 11 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 19 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 36 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 8 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 41 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [6 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1975 - M450 - P05 - 1-1.jpg](MANUALS/1975%20-%20M450%20-%20P05%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 24 to 40 dB _ Unity with externa ] pair of T5k 0hm resistors |
| **Noise** | (20 Hz to 20 kllz) 65 dBm (at 40 dB gain) 80 dBm. (at unity gain) |
| **Input impedance** | 5k ohm. 30k ohm (with externa] pair 0 [ T5k ohm resistors). |
| **Output isolation** | (not applicable): 90 dB or better from 20 Hz 10 20 kHz 'Maximum Input Leve] +30. dBm. Used a $ PROGRAM Or SUMMING AMPLIFIER |
| **Frequency response** | Harmonic Distortion ~10.25 dB from 20 Hz_ to 20 klz. Less than 0.25% Thi) from 20.Hz Lo 20 kHz 600 on Ia X i MuM, baLanced |
| **Source impedance** |  |
| &nbsp;&nbsp;Maximum output level | +30 dBm into 600 0 hmn 1oad, balanced. Output' Impedance Less than 35 ohm, 20 Hz Lo 20 kHzba ]anced Load [mpedance 600 ohm miniMUM. |
| **Phasing** | Low number termina ] 5 of input and output dre in phase |
| **Power requirement** | 25 volts dc 40 #26: MA quiescent current, Ma at +30 dBm output into 600 ohm. |
| **Ambient temperature** | 0.to 60 degrees Celsius wide 3.5&quot; high X 7.0&quot; Jeep (28 mm X 89 MM X 178 Mm) Dimens ons |

## Circuit description

From [1975 - M450 - vint P5.jpg](MANUALS/1975%20-%20M450%20-%20vint%20P5.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

M450 PROGRAM/ SUMM NG AMPLIFIER The two sections of 21 with their power booster output transistors Q1, Q2, Q3 and Ql provide the balanced summing (mixing) nput to the M450 Via pins 3 and 5 of the edge connector. One half of the balanced signa] is app] ied_ to pin 3 through_ the external summing (mixing) resistors (15 ko nomi na] each) to pin 6 of 21 through C5. From s igna] tandpoint, this point is virtually at ground potential and it is impractica] to measures igna] vo tage at this point. The second half of the balanced s igna] is applied to 5, Bi8 again through the external summing resistors, to pin of 21 through C6_ In addition the output of 21, pin is also summed through R13 to pin 8 of 2I _ Thus, at C15, which is located at the output of the summing pre-amp]ifier, the sum of all input voltages connected to the summing inputs will appear. When the unit is used as program amp ] i fier, the input signa] iS app] ied to pins 4 and 6 of the edge connector and then proceeds via on-board resistors to z1, presenting an input of approximately 5 k to the s igna ] source When used as summing amp] i fier the M450 is usually operating at unity gain, while as program amp] i fier the gain may From 24 to 40 dB = A11 gain changes of the amplifier are Facy litated by externa| resistance strappi on ins 9, 10 and ng 11 the feedback Be Effectively this changes oop tween pins 13 and 8 of ZI _ Since the selection of either pair of input terminals as we ] 1 as the gain of each amp 1 i fier is determined by connections made at the connector rather than inside the amp |ifier all M450 amplifiers within any given system can be freely interchanged without affecting system specifications and operation. Fo] owing the Pre-amp] i fier output at C15 is 12 dB per octave low pass filter comprised of R22 R52, R23, R24, C16 C17, C18 and C19, limiting the bandwidth beyond the audio pass band. The s igna] is then fed to pin 6 of 22 and subsequently to transistors Q9, Q10, Q11 and Q12. These transistors comprise

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlVHdjY3OHY2LUk/view?resourcekey=0-g2yyZqvwKMEixL-eOXCo0g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlVHdjY3OHY2LUk&resourcekey=0-g2yyZqvwKMEixL-eOXCo0g" width="240" alt="1975 - M450 - file.jpg"></a><br><sub>1975|8 · file</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

## 3-D model

[`MECHANICAL/M450.stl`](MECHANICAL/M450.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M450)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M450 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M450.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU041MmxkNDlHWmc/view?resourcekey=0-tdr-A8toNDeC5I0c5Q4gtg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU041MmxkNDlHWmc&resourcekey=0-tdr-A8toNDeC5I0c5Q4gtg" width="240" alt="1975 - M450 - 4-120-06-001.jpg"></a><br><sub>1975|8 · 4-120-06-001 · <a href="SCHEMATICS/1975%20-%20M450%20-%204-120-06-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ05SaWRQMlVLejQ/view?resourcekey=0-EBC-4E-PkP0SwMiLMsIBvQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ05SaWRQMlVLejQ&resourcekey=0-EBC-4E-PkP0SwMiLMsIBvQ" width="240" alt="1975 - M450 - 450-02-001 - PROGRAM SUMMIK AMOLIEIER GCALE SCHEMATIC.jpg"></a><br><sub>1975|8 · 450-02-001 - PROGRAM SUMMIK AMOLIEIER GCALE SCHEMATIC · <a href="SCHEMATICS/1975%20-%20M450%20-%20450-02-001%20-%20PROGRAM%20SUMMIK%20AMOLIEIER%20GCALE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkt1MU9VT2lfS2s/view?resourcekey=0-VXah4oRxC10mvVOrQB7YrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkt1MU9VT2lfS2s&resourcekey=0-VXah4oRxC10mvVOrQB7YrA" width="240" alt="1975 - M450 - 450-02-001.jpg"></a><br><sub>1975|8 · 450-02-001 · <a href="SCHEMATICS/1975%20-%20M450%20-%20450-02-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWldyZGtQR0g1dlE/view?resourcekey=0-_9eIPFScaQUhBZ5LYsr6sA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWldyZGtQR0g1dlE&resourcekey=0-_9eIPFScaQUhBZ5LYsr6sA" width="240" alt="1975 - M450 - P13 - Schematic.jpg"></a><br><sub>1975|8 · P13 - Schematic · <a href="SCHEMATICS/1975%20-%20M450%20-%20P13%20-%20Schematic%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKajg3T3RqMWM0Zmc/view?resourcekey=0-enPAIydlQsm6YOz3Bprhzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKajg3T3RqMWM0Zmc&resourcekey=0-enPAIydlQsm6YOz3Bprhzg" width="240" alt="1975 - M450 - P14 - Component Layout.jpg"></a><br><sub>1975|8 · P14 - Component Layout · <a href="SCHEMATICS/1975%20-%20M450%20-%20P14%20-%20Component%20Layout%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/17CIHtcSxLNnEo2mO3pcQSORLkRMoaxeV/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=17CIHtcSxLNnEo2mO3pcQSORLkRMoaxeV" width="240" alt="19xx - M450 - DOC - 01450-02-001 - USE THESE COHPONENTS ONLY WHEN SPECIFIED.jpg"></a><br><sub>19xx - M450 - DOC - 01450-02-001 - USE THESE COHPONENTS ONLY WHEN SPECIFIED · <a href="SCHEMATICS/19xx%20-%20M450%20-%20DOC%20-%2001450-02-001%20-%20USE%20THESE%20COHPONENTS%20ONLY%20WHEN%20SPECIFIED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWpsTmp1ZVFlb2c/view?resourcekey=0-1p7ZCEBSPVhCl_MNxR8FlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWpsTmp1ZVFlb2c&resourcekey=0-1p7ZCEBSPVhCl_MNxR8FlA" width="240" alt="1975 - M450 - P15 - Pin Out.jpg"></a><br><sub>1975|8 · P15 - Pin Out · <a href="PINOUTS/1975%20-%20M450%20-%20P15%20-%20Pin%20Out%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

Read from 7 pinout pictures (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 15 of 15 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +25 V | power |  | high |
| 2 | N/C | nc |  | high |
| 3 | SUMMING INPUT | in | SUMMING INPUT | high |
| 4 | PROGRAM INPUT | in | PROGRAM INPUT | high |
| 5 | SUMMING INPUT | in | SUMMING INPUT | high |
| 6 | PROGRAM INPUT | in | PROGRAM INPUT | high |
| 7 | INPUT SHIELD | shield | PROGRAM INPUT shield | high |
| 8 | COMMON | ground |  | high |
| 9 | GAIN SET | strap | GAIN SET | high |
| 10 | GAIN SET | strap | GAIN SET | high |
| 11 | GAIN SET | strap | GAIN SET | high |
| 12 | OUTPUT | out | OUTPUT | high |
| 13 | OUTPUT | out | OUTPUT | high |
| 14 | N/C | nc |  | high |
| 15 | -25 V | power |  | high |

**Straps:** GAIN SET: P1-9 P1-10 P1-11

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU3hlcVprNUdoWUU/view?resourcekey=0-O8vEjNEj7oCU-nAqVkZQKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU3hlcVprNUdoWUU&resourcekey=0-O8vEjNEj7oCU-nAqVkZQKQ" width="240" alt="1975 - M450 - P01 - Cover.jpg"></a><br><sub>1975|8 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2Q3VTFLc0JnOVU/view?resourcekey=0-r9MnrM9AatLE_9BvA2K5zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2Q3VTFLc0JnOVU&resourcekey=0-r9MnrM9AatLE_9BvA2K5zg" width="240" alt="1975 - M450 - P02.jpg"></a><br><sub>1975|8 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFhTODg2YzR4ZVk/view?resourcekey=0-gAvxKtd16XJlIlEPN8Ukuw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFhTODg2YzR4ZVk&resourcekey=0-gAvxKtd16XJlIlEPN8Ukuw" width="240" alt="1975 - M450 - P04 - Warranty.jpg"></a><br><sub>1975|8 · P04 - Warranty</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQy1OQ3pEMmN3SkE/view?resourcekey=0-jwNPg1WAFCTCf-qcOQ9AmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQy1OQ3pEMmN3SkE&resourcekey=0-jwNPg1WAFCTCf-qcOQ9AmA" width="240" alt="1975 - M450 - P05 - 1-1.jpg"></a><br><sub>1975|8 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb0Q5NWlhZDFYNEE/view?resourcekey=0-z9hU-nE3bO4s0XE2_B4zFA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb0Q5NWlhZDFYNEE&resourcekey=0-z9hU-nE3bO4s0XE2_B4zFA" width="240" alt="1975 - M450 - P06 - 2-1.jpg"></a><br><sub>1975|8 · P06 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVzA2bXpfYU9tb0U/view?resourcekey=0-BgXnA6-uNmZQepJ7qZOsnQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVzA2bXpfYU9tb0U&resourcekey=0-BgXnA6-uNmZQepJ7qZOsnQ" width="240" alt="1975 - M450 - P07 - 3-1.jpg"></a><br><sub>1975|8 · P07 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUhCbUZVMWJQRW8/view?resourcekey=0-k8WZuxLlyBSoDpoqFpMEfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUhCbUZVMWJQRW8&resourcekey=0-k8WZuxLlyBSoDpoqFpMEfQ" width="240" alt="1975 - M450 - P07 - 3-2.jpg"></a><br><sub>1975|8 · P07 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUliOFFoWV9CUnc/view?resourcekey=0-RAuL1Q3JSQEFzkZ4tm8qhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUliOFFoWV9CUnc&resourcekey=0-RAuL1Q3JSQEFzkZ4tm8qhQ" width="240" alt="1975 - M450 - P08 - 4-1.jpg"></a><br><sub>1975|8 · P08 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekpJY0pCODNZR1k/view?resourcekey=0-p7-wrOkHhVj6lz6UJWWpCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekpJY0pCODNZR1k&resourcekey=0-p7-wrOkHhVj6lz6UJWWpCA" width="240" alt="1975 - M450 - P09 - 5-1.jpg"></a><br><sub>1975|8 · P09 - 5-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2w2Q2U1a1hOajA/view?resourcekey=0-PbENjkC9wHVz--iHA9GHhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2w2Q2U1a1hOajA&resourcekey=0-PbENjkC9wHVz--iHA9GHhQ" width="240" alt="1975 - M450 - P10 - 5-2.jpg"></a><br><sub>1975|8 · P10 - 5-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbWhaZ1RSeERhOXc/view?resourcekey=0-EauwXWNbjaZk4UUb0wmBZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbWhaZ1RSeERhOXc&resourcekey=0-EauwXWNbjaZk4UUb0wmBZQ" width="240" alt="1975 - M450 - P11 - 5-3.jpg"></a><br><sub>1975|8 · P11 - 5-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR01nb01VeTQyOFk/view?resourcekey=0-nmBrRLUoIb2a5aGlu3kD0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR01nb01VeTQyOFk&resourcekey=0-nmBrRLUoIb2a5aGlu3kD0Q" width="240" alt="1975 - M450 - P12 - 5-4.jpg"></a><br><sub>1975|8 · P12 - 5-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjRickJ5ZDl4ZEk/view?resourcekey=0--DreTS7FjUUul8bUZl2yiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjRickJ5ZDl4ZEk&resourcekey=0--DreTS7FjUUul8bUZl2yiQ" width="240" alt="1975 - M450 - Program Summing Amp (2).pdf"></a><br><sub>1975|8 · Program Summing Amp (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWhpdFFhcjlyVjA/view?resourcekey=0-Qh9UrlbdHh0Wdz5bzzyipw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWhpdFFhcjlyVjA&resourcekey=0-Qh9UrlbdHh0Wdz5bzzyipw" width="240" alt="1975 - M450 - Program Summing Amp.pdf"></a><br><sub>1975|8 · Program Summing Amp</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ1ZPTDBTSkpqclk/view?resourcekey=0-skHorCrM3KRUsaht60IWQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ1ZPTDBTSkpqclk&resourcekey=0-skHorCrM3KRUsaht60IWQg" width="240" alt="1975 - M450 - vint P1.jpg"></a><br><sub>1975|8 · vint P1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0lUSXBxVUZlSDA/view?resourcekey=0-NUfGI-qA2CmOpgGDuXhyfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0lUSXBxVUZlSDA&resourcekey=0-NUfGI-qA2CmOpgGDuXhyfg" width="240" alt="1975 - M450 - vint P10.jpg"></a><br><sub>1975|8 · vint P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY21tSXB5UWR0TlU/view?resourcekey=0-b-gPcio8GSHrNem_ZjH65Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY21tSXB5UWR0TlU&resourcekey=0-b-gPcio8GSHrNem_ZjH65Q" width="240" alt="1975 - M450 - vint P12.jpg"></a><br><sub>1975|8 · vint P12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUZHR29aeEgzbGc/view?resourcekey=0-sApfqfR-WQ8p2mbDbT85Tw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUZHR29aeEgzbGc&resourcekey=0-sApfqfR-WQ8p2mbDbT85Tw" width="240" alt="1975 - M450 - vint P3.jpg"></a><br><sub>1975|8 · vint P3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMG1tU1JCa29tOFk/view?resourcekey=0-2XaZJLkYozZz84NVEyEIQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMG1tU1JCa29tOFk&resourcekey=0-2XaZJLkYozZz84NVEyEIQA" width="240" alt="1975 - M450 - vint P4.jpg"></a><br><sub>1975|8 · vint P4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDBwNWNEYnRCZ1E/view?resourcekey=0-cE2TtcCcqrORmgoFQFGdGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDBwNWNEYnRCZ1E&resourcekey=0-cE2TtcCcqrORmgoFQFGdGg" width="240" alt="1975 - M450 - vint P5.jpg"></a><br><sub>1975|8 · vint P5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOXpRQXB3eTQ0NFU/view?resourcekey=0-dWcj9NRaoB9n1nu8_UNTWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOXpRQXB3eTQ0NFU&resourcekey=0-dWcj9NRaoB9n1nu8_UNTWQ" width="240" alt="1975 - M450 - vint P6.jpg"></a><br><sub>1975|8 · vint P6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNG5uSmhraFdWS2s/view?resourcekey=0-gEM-o60hZlUQ_yagiscGtQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNG5uSmhraFdWS2s&resourcekey=0-gEM-o60hZlUQ_yagiscGtQ" width="240" alt="1975 - M450 - vint P7.jpg"></a><br><sub>1975|8 · vint P7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDNxbnlXZ1JwVDA/view?resourcekey=0-gB_LL-9tOYqvL1l-5JiRxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDNxbnlXZ1JwVDA&resourcekey=0-gB_LL-9tOYqvL1l-5JiRxw" width="240" alt="1975 - M450 - vint P8.jpg"></a><br><sub>1975|8 · vint P8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXdrdDc1N2FvV2c/view?resourcekey=0-sYZ7jN5naoTxmbNqDZ9QGQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXdrdDc1N2FvV2c&resourcekey=0-sYZ7jN5naoTxmbNqDZ9QGQ" width="240" alt="1975 - M450 - vint P9.jpg"></a><br><sub>1975|8 · vint P9</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEprSDRPNWpWY00/view?resourcekey=0-j99pmvW18YEFvuOF8FAREQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEprSDRPNWpWY00&resourcekey=0-j99pmvW18YEFvuOF8FAREQ" width="240" alt="1977 - M450 - P03 - TOC.jpg"></a><br><sub>1977|10 · P03 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSUFYUFpHdjJNVmc/view?resourcekey=0-4vBgxlqpPOiohIBD9wS3Cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSUFYUFpHdjJNVmc&resourcekey=0-4vBgxlqpPOiohIBD9wS3Cw" width="240" alt="1977 - M450 - vint P11.jpg"></a><br><sub>1977|10 · vint P11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTzN6b2R5ZmtJR3M/view?resourcekey=0-eW4_Jisl52dgi-9JCFBOQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTzN6b2R5ZmtJR3M&resourcekey=0-eW4_Jisl52dgi-9JCFBOQA" width="240" alt="1977 - M450 - vint P2.jpg"></a><br><sub>1977|10 · vint P2</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - 450-02-001 - PROGRAM SUMMING AMPLIFIER SCHEMATIC - DRN DM - ISS 7.kicad_sch](KICAD/1974%20-%20450-02-001%20-%20PROGRAM%20SUMMING%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%207.kicad_sch)
- [1975 - 450-01-001 - M450A PROGRAM SUMMING AMPLIFIER FUNCTIONAL DIAGRAM - DRN AAS - ISS 1.kicad_sch](KICAD/1975%20-%20450-01-001%20-%20M450A%20PROGRAM%20SUMMING%20AMPLIFIER%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20AAS%20-%20ISS%201.kicad_sch)
- [1975 - M450 - 450-02-001 - PROGRAM SUMMIK AMOLIEIER GCALE SCHEMATIC.kicad_sch](KICAD/1975%20-%20M450%20-%20450-02-001%20-%20PROGRAM%20SUMMIK%20AMOLIEIER%20GCALE%20SCHEMATIC.kicad_sch)
- [1975 - M450 - 450-02-001.kicad_sch](KICAD/1975%20-%20M450%20-%20450-02-001.kicad_sch)
- [1975 - M450 - P13 - Schematic.kicad_sch](KICAD/1975%20-%20M450%20-%20P13%20-%20Schematic.kicad_sch)
- [1978 - 450-02-003 - M450B PROGRAM SUMMING AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 3.kicad_sch](KICAD/1978%20-%20450-02-003%20-%20M450B%20PROGRAM%20SUMMING%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%203.kicad_sch)
- [19xx - M450 - DOC - 01450-02-001 - USE THESE COHPONENTS ONLY WHEN SPECIFIED.kicad_sch](KICAD/19xx%20-%20M450%20-%20DOC%20-%2001450-02-001%20-%20USE%20THESE%20COHPONENTS%20ONLY%20WHEN%20SPECIFIED.kicad_sch)
- [M450.kicad_sym](KICAD/M450.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
