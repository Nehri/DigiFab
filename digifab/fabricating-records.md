Fabricating "Vinyl" Records
======================
---
Investigators
------------------
---
Aaron Schaer, Michelle Ross and Steven Hernandez
Objective
-------------
---
The principle objective of this project is the comparative analysis of techniques for the development of customized conventional records with attention to time, cost, durability, fidelity, accessibility of materials, and aesthetics.

The project aims to develop software for the conversion of audio waveforms in a conventional format (MP3) to valid model files in STL and DXF formats which can be used for 3D Printing or Laser Etching records respectively. This software will then be applied to a variety of conventional materials (PLA, acrylic, plywood) and possible more exotic materials as well (chocolate, wax).

The tangible results of the project will be a collection of fabricated records across a multitude of media produced by a variety of fabrication methods. This would be accompanied by our analytic data on each design method.
Background and Previous Work
-------------------------------------------
---
Despite conventional wisdom suggesting that the vinyl record format is dying, US sales of records have been on the rise over the last seven years. Vinyl sales have increased more than sixfold from 1,880,000 in 2008 to 11,900,000 in 2015 in a time-span in which digital records and streaming services continue to drop the overall sale of physical records (CDs)[1](http://www.nielsen.com/content/dam/corporate/us/en/reports-downloads/2016-reports/2015-year-end-music-report.pdf.pdf) [2](http://www.rollingstone.com/music/news/radiohead-neutral-milk-hotel-help-vinyl-sales-almost-double-in-2008-20090108). Demand for vinyl records is increasing, but vinyl records remain expensive and often difficult to locate/acquire. As such, the ability to produce one's own is enticing.

Amanda Ghassaei has had success in projects both in 3D printing and laser cutting records [3](http://www.amandaghassaei.com/projects/3D_printed_record/) [4](http://www.amandaghassaei.com/projcts/laser_cut_record/). Her workflow developed for the conversion of raw audio information to printable file formats is simple and attractive for replication.
Technical Approach
Timeline
-------------
---
Week 1: Develop an algorithm for converting an mp3 file into .stl or .dfx format. This will require analyzing the mp3 file for necessary details and translating each musical detail into grooves in a model (or etches to be made, in the case of laser cutting). See link 3 above for a person's previous attempt at this algorithm, which can serve as a useful starting place for our own project.
Week 2: Debug the algorithm from week 1 and extend it. We would like to enhance the algorithm to support multisided records, which will require us to modify the code from link 3 significantly.
Week 3: Test record printing and cutting in several easy and typical materials. We will use basic materials like PLA, wood, and acrylic to print and cut the records using the algorithm developed in the previous weeks while taking note of many aspects of the prints/cuts, including audio quality, durability, playability, time to make, and accuracy.
Week 4: Expand into as-of-yet untested materials like chocolate, wax, aluminum, etc. These will take records outside of their normal domain and allow us to test the changes to the above categories that are caused when using exotic materials.
Week 5: Create a user-facing application for the algorithm that is polished and user-friendly, allowing any (public domain) song to be output into either .stl or .dfx format. Synthesize the data from weeks 3 and 4 and chart it to allow for easy analysis and comprehension.
Materials
-------------
---
* Normal and exotic materials for printing and laser-cutting (PLA filament, plywood, aluminum, acrylic, chocolate, wax, icing)
* Access to a large(r) 3D printer, such as the Connex in the Fab Lab
* Access to a laser cutter
* Audio Spectrometer (Optional)
* Record player (already owned)
Notes
-------------
---
