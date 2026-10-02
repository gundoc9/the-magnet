# Sources

How each source was checked for this app, with a link (2 October 2026). The grade printed on each card is the status given here.

- **Panych and Madore** - Panych LP, Madore B. The physics of MRI safety. J Magn Reson Imaging 2018;47(1):28-43.  
  Read in full. Figures never redrawn; every picture is computed from the equations. Cards: Always on, The pull, The twist, The line, Heat, Noise, The ECG in the bore. [Open the source](https://doi.org/10.1002/jmri.25761)
- **Wilson** - Wilson SR, Shinde S, Appleby I, et al. Guidelines for the safe provision of anaesthesia in magnetic resonance units 2019. Anaesthesia 2019;74(5):638-650.  
  Read in full. Open access, CC BY-NC-ND; cited and described, not adapted. The Association's page lists the review deadline as extended to 2026. Cards: Always on, The pull, The twist, The line, Labels, Heat, Noise, The ECG in the bore, The arrest, The quench. [Open the source](https://doi.org/10.1111/anae.14578)
- **ASA** - American Society of Anesthesiologists Task Force on Anesthetic Care for Magnetic Resonance Imaging. Practice advisory on anesthetic care for magnetic resonance imaging: an updated report. Anesthesiology 2015;122(3):495-520.  
  Read in full. Listed by the ASA as current (page updated August 2026). Cards: Always on, The twist, The line, Labels, Heat, The ECG in the bore, The arrest, The quench. [Open the source](https://doi.org/10.1097/ALN.0000000000000458)
- **MHRA** - Medicines and Healthcare products Regulatory Agency. Safety Guidelines for Magnetic Resonance Imaging Equipment in Clinical Use. 5th edition, V5.0.3, September 2026.  
  Read in full: sections 1 to 4.3 from the GOV.UK text, the rest of the main text and Appendices 1 to 6 from the PDF (2 October 2026). Section 4.4 (emergency procedures), 5.3.7 (burns), 5.3.10 (monitoring), 5.6 (anaesthesia), 6.2.5 (the quench button) and Appendix 1 (cryogens) are cited directly on the Heat, ECG, Arrest and Quench cards. Cards: Always on, The pull, The twist, The line, Labels, Heat, Noise, The ECG in the bore, The arrest, The quench. [Open the source](https://www.gov.uk/government/publications/safety-guidelines-for-magnetic-resonance-imaging-equipment-in-clinical-use)
- **ACR** - American College of Radiology. ACR Manual on MR Safety, 2026.  
  Chapters 1 to 3 read (zones, the 0.9 mT line). Chapter 14 (emergencies, quench) not reached. Cards: The line, The arrest, The quench. [Open the source](https://www.acr.org/Clinical-Resources/Clinical-Tools-and-Reference/radiology-safety/mr-safety)
- **RCoA** - Royal College of Anaesthetists. Guidelines for the Provision of Anaesthesia Services in the Non-theatre Environment 2026 (GPAS Chapter 7).  
  MRI section read. MRI recommendations 3.35 to 3.42 read; full review due January 2028. Cards: Always on, The ECG in the bore, The arrest. [Open the source](https://www.rcoa.ac.uk/chapter-7)
- **Kolandaivelu and colleagues** - Kolandaivelu A, Bruce CG, Seemann F, et al. Evaluation of 12-lead electrocardiogram at 0.55T for improved cardiac monitoring in magnetic resonance imaging. J Cardiovasc Magn Reson 2024;26(1):101009.  
  Read in full through PubMed Central. Cards: The ECG in the bore. [Open the source](https://doi.org/10.1016/j.jocmr.2024.101009)
- **Formica and Silvestri** - Formica D, Silvestri S. Biological effects of exposure to magnetic resonance imaging: an overview. Biomed Eng Online 2004;3:11.  
  Read in full. Cards: The ECG in the bore. [Open the source](https://doi.org/10.1186/1475-925X-3-11)
- **Kopanoglu and colleagues** - Kopanoglu E, Steckner M, Hoff MN, et al. MRI and implant safety at low-field and ultralow-field strengths. J Magn Reson Imaging 2026;63(2):364-377.  
  Read in full. Cards: Labels, Heat, Noise. [Open the source](https://doi.org/10.1002/jmri.70168)
- **Baker and colleagues** - Baker C, Nugent B, Grainger D, Hewis J, Malamateniou C. Systematic review of MRI safety literature in relation to radiofrequency thermal injury prevention. J Med Radiat Sci 2024;71(3):445-460.  
  Abstract only. Cards: Heat. [Open the source](https://doi.org/10.1002/jmrs.800)

## The register

Every number a card states is held in a register of 144 entries, each with its source, location and grade, and the 26 derived numbers are recomputed by a gate before any build. The register is published in the app, under the Numbers tab on the front page (138 entries: the six left out are four claims that stand behind the front page rather than a card, one that records a conflict between sources and one about a number no card prints). The model's own numbers (where the pull passes the object's weight, where the lines cross the axis, the field at the pump) are recomputed from the field model by the same gate.

## The pictures

The rooms and the scanner are drawn by the page, closed as they look in the department, to the scale of the computed magnet; the field, the curves, the lines, the marks and every label are drawn over them. The children, the staff and some of the equipment are illustrations created in BioRender under the author's licence (Created in BioRender. Sivasankara, G. (2026) BioRender.com): the child on the table, the child in the bore seen from above (with the arms moved for two of the poses), the child's head, the infusion pump, and the people, the trolley and the crash trolley seen from above.

## The model

An illustrative actively shielded 3 T magnet: a main coil (radius 0.44 m, length 1.50 m) and a counter-wound shield coil (radius 0.86 m, length 1.60 m) whose dipole moment cancels the main coil's, scaled so the field at the centre is 3 T; the unshielded variant is the main coil alone at the same centre field. The pull follows Panych and Madore's equations 2 to 4 with their Fig 2 object (C 10 m/T², D 0.01, saturation 2.5 T). The twist is the moment times the field, as a share of its value at the centre; the holding-force ratio is their equation 6 evaluated at the object's position. The 1.5 T magnet on the Labels card is the same design at half the current.
