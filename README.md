# The magnet

A teaching app on MRI safety physics for the anaesthetist, written for the paediatric list. Ten cards, one hazard each, with a picture computed from the physics and a control that changes it.

- **The magnet:** Always on, The pull, The twist, The line, Labels.
- **Radio waves and noise:** Heat, Noise.
- **The monitor:** The ECG in the bore.
- **When it goes wrong:** The arrest, The quench.

Every card ends with "On the list", the things the reader does differently on the next MRI list, one question under "Before you go" with the answer under a tap, and its sources with what was read.

The front page has four tabs: the terms (the ten cards), the list (the first thing from each card on one page, with a print button), the sources, and the numbers (every number the cards state, with its source, the place in the source and what was read). The same list is in `the-magnet-list-a4.pdf`, one A4 page for the department wall, with the address and a QR code.

Each picture carries a spoken description for screen readers, which changes with the controls. On a keyboard, the right and left arrows move between cards and Escape returns to the front page.

The rooms, the scanner and everything computed are drawn by the page: the magnet is an illustrative 3 T design of two coils, computed from the textbook equations, and it is no particular scanner. The children, the staff and some of the equipment are illustrations created in BioRender (Created in BioRender. Sivasankara, G. (2026) BioRender.com). The pull and the twist follow Panych and Madore's equations, the ECG distortion is sized from Kolandaivelu and colleagues' measurements, and the plans of the unit and the magnet room are imagined. Manufacturers supply the field and gradient plots for each scanner, so the map of your own unit exists.

Nothing leaves the device: one HTML file with its typeface embedded, nothing fetched from elsewhere, no tracking. It opens on the list of cards every time.

Files: `index.html` (the app), `the-magnet-list-a4.pdf` (the ten things on one A4 page), `the-magnet-icon-180.png` (home-screen icon), `the-magnet-card.png` (link preview), `SOURCES.md`, `LICENSE`.

Dr Ganesh Sivasankara · MD · FRCA · FCARCSI · Consultant Anaesthetist
