# Probe synthesis from complex-oligo pools
This protocol was written by the Boettiger Lab, and is adapted from our previously published protocols.

## Methods
All steps are carried out at room temperature, unless indicated otherwise.

#### Limited Cycle PCR (per 50 μl reaction)
1. Prepare on ice:
	* 15 μl ddH2O.
	* 25 μl Phusion Hot-start Master Mix.
	* 2.5 μl 10 µM Forward primer.
	* 2.5 μl 10 µM Reverse primer with T7 promoter sequence.
	* 2.5 μl diluted Oligopaints library (~1 ng/uL is a good start).
	* 2.5 μl 20X EvaGreen.

2. Run reactions on a Real-Time (RT) PCR machine, stopping the reaction for each tube while it is still in the exponential growth phase (i.e., before it reaches saturation). A calibration run may be necessary to identify when this will happen. PCR protocol:
	1. 	Incubate at 98°C for 3 minutes.
	2. 	Incubate at 98°C for 5 seconds.
	3. 	Incubate at 65°C for 10 seconds.
	4.  Incubate at 72°C for 14 seconds.
	5.  Image progress 
	6.  Incubate at 72°C for 8 seconds.
	7.  Cycle through steps 2.1.2 and 2.1.6 approximately 15-28 times.
	8.  Be sure to stop the reaction only when at 72°C or below.  Stopping during the melting phase will result in cross-annealed hybrids.  

3. OPTIONAL: validate PCR reaction by running 2 µl out on a 2% agarose borax gel. 
	1. Dissolve 2 g agarose in 100 ml borax solution by boiling for 30 seconds.
	2. Cast the hot solution and let sit until gelled. (incubate at 4C to accelerate gelling). 
	3. A satisfying result will feature a single band, typically at 120-160 bp, depending on the length of the library. 
	4. A failed result may look like:
		- Two strong bands, one higher-weight than the target, indicates the presence of cross-annealed hybrids resulting from over amplification.
		- A single band of than expected molecular weight, indicating all product is cros hybridized.
		- decreasing the number of cycles and/or increasing the primer concentration may help.

#### PCR cleanup (50 µl reaction)
  1.	In a 1.5 ml tube, add 350 μL Zymo DNA binding buffer to ~50 μL of PCR product.
  2.	Transfer to a Zymo DCC-5 column and spin at >10,000 g for 30 seconds.
  3.	Add 200 µl DNA Wash Buffer to column and spin at >10,000 g for 30 seconds.
  4.	Repeat the wash step.
  5.	Discard flow-through by aspirating the collection tube dry.
  6.	Spin at >10,000 g for 1 minute to remove residual buffer.
  7.	Transfer column to clean 1.5 ml tube.
  8.	Incubate at room temperature for 1 minute.
  9.	Elute DNA in 11 µl ddH2O.

#### T7 reaction (23 μl reaction)
  1.	Prepare on ice in RNase-free environment:
	* 10 µl PCR product.
	* 10 µl NTP buffer mix (from HiScribe kit).
	* 2 µl T7 Pol Mix (from HiScribe kit).
		* Note: This enzyme/buffer mix is the most expensive component of the reaction. Experiments suggest reducing the concentration of enzyme at this step will reduce product yield. 
	* 1 µl RNase inhibitor.
		* Note: Any RNase inhibitor should work at this step, it is not necessary to use the more expensive RNasin.
  2.	Incubate at 37˚C for 4-16 hrs.

#### RT reaction (50 µl reaction)
  1.	Prepare on ice in RNase-free environment:
	* 4 µl dNTP (10 mM each).
	* 10 µl RT Buffer from Maxima H Minus kit.
	* 6 µl 200 μM labeled or unlabeled primer.
		* Note: When using labeled primer, you may wish to run a test scale-reaction and validate efficiency on a gel first.
		* Note: If a substantial primer band is observed in the PAGE gel below, use less primer.    
	* 1 µl or less Maxima H Minus RT enzyme.
		* 1 µl is sufficient for up to a 10X master-mix. It is not recommended however to pipette less than 1 µl of the viscous glycerol solution. 
	* 4 µl RNasin RNase inhibitor.
		* Note: It is essential to use an RNase inhibitor engineered to work at 50C, RNasin does, most do not.
	* All RNA (+enzyme buffer mix) from T7 reaction (20 uL).
		* Note: It is recommended to add these components to the same PCR tube used for the T7 reactions.  The 23 uL T7 reaction will experience some evaporation, so the final concentration is closer to 20 uL.
  2.	Incubate at 50˚C for 1 hour (no pre-denaturing step required).
  3.	Digest remaining RNA:
	* Mix 1:1 0.5 M EDTA and 1 M NaOH.
	* Add 25 µl of the NaOH-EDTA solution.
	* Heat at 95˚C for 10 minutes.
  4.	Recommended: Test reaction product by running 2 ul out on a 15% urea TBE gel.  Use urea-loading buffer.  
	* Run gel in 60°C water bath for ~40 minutes to ensure probe is denatured. This allows for clear separation between the RT primer and the desired ssDNA probe.
	*  80% or more incorporation of the RT primer would be a satisfying outcome.

#### Probe Cleanup
1.	Add 150 μl Oligo binding buffer to a clean 1.5 mL tube. 
	* (The volume of Oligo binding buffer added should 2X the volume of the sample after addition of NaOH-EDTA; 2 x 75 µl = 150 µl).
3.	Add NaOH-treated RT product (75 μL) to each tube and mix by pipetting.	
2.	Add 600 μL 100% Ethanol to each tube and mix. 
	 * (The total volume of ethanol added should be 8X the volume of the sample after addition of NaOH-EDTA; 8 x 75 µl = 600 µl).
3.	Transfer the solution of one tube to a Zymo **DCC-25** column, spin at ≥10,000 g for 30 seconds, and discard washthrough. 
	- Note 1: The maximum capacity of the column is 800 µl. Larger volumes may be split over two spins. 
	- Note 2: High concentration probes may saturate the DCC-5 column so DCC-25s are recommended.   
4.	Add 750 μl DNA Wash Buffer.
5.	Spin at >10,000 g for 30 seconds and discard flow-through.
6.	Spin at ≥10,000 g for 30 seconds to remove excess buffer.
7.	Transfer column to a clean 1.5 ml tube.
8.	Elute in 30 - 60 μl ddH2O.
	* yield is often better by eluting in a higher volume of water and concentrating the probe later in a rotaevap. 
9.	Measure final probe concentration.


## Materials
All solutions should be prepared using distilled, deionized water (ddH2O). Take care to avoid nuclease contamination, particularly from DNases. The recipes provided here for stock solutions will support many samples, while the rest are intended for a single sample.

* PCR amplification of Oligopaints library
  1.	Phusion Hot-start Master Mix (New England BioLabs, M0536S).
  2.	Forward primer.
  3.	Reverse primer with T7 promoter sequence (e.g., TAATACGACTCACTATAGGG; e.g., IDT) appended to its 5' end.
  4.	Oligopaints library (synthesized by, e.g., CustomArray).
  5.	A fluorescent intercalating dye for real-time PCR, such as EvaGreen Dye (20X in ddH2O; Biotium, 31000) or equivalent.

* PCR cleanup and gel electrophoresis
  1.	DNA Clean & Concentrator-5 (DCC-5) kit (Zymo Research, D4013).
  2.	6X Orange DNA Loading Dye (ThermoFisher Scientific, R0631).
  3.	LE Agarose (GeneMate, E-3120-500).
  4.	Borax solution: 1 g anhydrous sodium tetraborate (Sigma-Aldrich, 221732), in 1 liter of ddH2O.

* T7 Reaction
  1.	HiScribe T7 Quick High Yield RNA Synthesis Kit (New England BioLabs, E2050S).
  2.	RNasin Plus RNase Inhibitor (Promega, N2611).

* Reverse Transcription (RT)
  1.	Maxima H Minus RT Transcriptase (ThermoFisher Scientific, EP0751).
  2.	dNTP Mix – 10 mM each (Thermo Fisher, R0191).
  3.	15% Mini-PROTEAN TBE-Urea Precast Gels (Bio-Rad, 4565054), or make your own (see [PAGEgelCasting protocol](https://github.com/BoettigerLab/protocols/blob/master/PAGEgelCasting.md))
  4. Urea-loading buffer (Thermo Fisher, LC6876).

* Probe cleanup
  1.	DNA Clean & Concentrator-25 (DCC-25) kit (Zymo Research, D4005).
  2.	Oligo binding buffer (Zymo, D4060-1-40).
