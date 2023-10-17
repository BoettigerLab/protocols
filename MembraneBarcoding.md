# Cell Surface Barcode Labeling
## Introduction
Here, two sequential protocols are provided for: 1) synthesis and workup of click chemistry-ready methyltetrazine oligo amides from commercially available amine oligos 2) labeling of fixed cells with one or more barcodes for multiplexed readout
## Procedure A: Oligo Modification
### Materials
* 50 mM sodium borate buffer pH 8.5
	- Ideal if you produce concentrated stocks infrequently (~0.20-0.25 M) and dilute to working concentration and correct pH using NaOH and/or HCl such that working solution lasts no more than a year at RT
* 500 µM 3’-modified amino oligo in 50 mM sodium borate buffer pH 8.5
	- Order barcode with same sequence as found in primary probe set that hybridizes to adapter with standard desalting, then suspend in appropriate volume of 50 mM sodium borate buffer for 500 µM final concentration
* DMSO
	- Purchase anhydrous, store in desiccator @RT
* 10 mM Methyltetrazine-NHS ester (red)
	- Prepare by adding anhydrous DMSO to original tube powder arrives in, then dilute further with DMSO to make working aliquots, store at -20 °C
* 100% and 70% EtOH
	- Store at -20 °C
* 3M NaCl
* 10 mM HEPES pH 7.2
	- Dilute ~10 mL working solution from 1 M stock, store at 4 °C


### Procedure
1. In 1.5 mL microcentrifuge tube, add 25.0 µL 3’ amine-modified oligo in 50 mM sodium borate buffer, 8.2 µL 10 mM Methyltetrazine-NHS ester, 41.8 µL DMSO, incubate protected from light for 30 minutes with agitation
2. After 30 minutes, add another 8.2 µL 10 mM Methyltetrazine-NHS ester, then add once again after an additional 30 minutes
3. After the 90-minute reaction, quench by adding 180 µL 50 mM sodium borate buffer and 30 µL 3 M NaCl, then add 750 µL ice cold 100% EtOH
4. Precipitate @ -80 °C overnight
5. Transfer contents to ultracentrifuge tubes, balance with analytical balance, and spin at 20,000 xg for 30 minutes at 4 °C (see Barna lab for TLA 120.2 rotor, we have model 343778 tubes)
6. Wash twice with 750 µL 70% EtOH, ensuring not to disrupt the pellet (don’t mix pipette). Additionally, let pellet dry for ~10 minutes in fume hood until nearly all ethanol has evaporated
7. Resuspend pellet in 100 µL cold HEPES buffer
8. Quantify recovery with A260 and manufacturer’s listed molar extinction coefficient. Typical concentration is around ~80 µM.
	
Example calculation:
$[Oligo]= A_260/ε 10^6=14.872/(181700 1/(M-cm)) 10^6 (µM)/M=81.8µM$

## Procedure B: Cell Labeling

### Materials
* 1 mM TCO-PEG4-TFP Ester (purple)
	- Prepare in same fashion as Methyltetrazine-NHS ester
* 5 mM Methyltetrazine-PEG4-Amine (green)
	- Prepare in same fashion as Methyltetrazine-NHS ester
* 1 M Tris HCl
* 1X PBS

### Procedure
1. Cell collection and fixation:
	- For adherent cells, collect cells by trypzinization. Count cells.
	- Fix cells in suspension in 4% PFA for 10 min, ideally on a nutator.
	- Following 3 washes in 1xPBS, resuspend cells in 70% EtOH in 1xPBS and store at -20C. I like to store them at 1-10 M cells/ul.
2. Fixed cells can then be labelled. 
	- I (Tonia) found that more cells is better as there is some loss at each wash. Scott used ~400’000, I went up to 5 M with the same amount of reagents below.
3. All subsequent steps, unless noted otherwise, should be carried out independently for each cell population
	- If freshly prepared, wash once with PBS
	- If sourced from stock in 70% EtOH in PBS stored at -20 °C, wash twice with PBS
4. Resuspend in 100 µL PBS
5. Add 4 µL 1 mM TCO-PEG4-TFP Ester, mix with tip, incubate for 5 min @RT protected from light
6. Add 6 µL of each methyltetrazine oligo amide prepared in procedure A, incubate for 30 min @RT protected from light
7. Add Methyltetrazine-PEG4-Amine for final concentration of 50 µM and Tris HCl to 10 mM final concentration, incubate for 5 min @RT
8. Pool all cell populations into a single tube
9. Dilute twofold with 1X PBS, spin down and resuspend in 1X PBS
10. Wash 3X with PBS
11. Resuspend in 40 µL 70% EtOH in PBS
