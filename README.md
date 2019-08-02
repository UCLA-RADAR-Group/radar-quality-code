Background

The Minor Planet Center has used an uncertainty parameter and [quality code](https://minorplanetcenter.net/iau/info/UValue.html) to indicate the reliability of orbital fits for decades. Quality codes also exist for [asteroid lightcurves](https://sbnarchive.psi.edu/pds4/non_mission/ast-lightcurve-database_V2_0/document/pds_readme.txt) and for [asteroid stellar occultations](https://sbnarchive.psi.edu/pds4/non_mission/smallbodiesoccultations_V2_0/document/bundle_description.txt). Because the quality of radar size estimates vary widely, we wish to develop and assign a quality code to radar results.

Proposed scale:

A numeric code is used to indicate the quality of a size (effective diameter) estimate for radar-observed asteroids and comet nuclei. The quality code parameter "Q" ranges from 0 (incorrect) to 4 (well-defined):
* Q = 0 → Result later proven incorrect
* Q = 1 → Result based on fragmentary, inconclusive, low-SNR, or low-resolution data. Size may be completely wrong.
* Q = 2 → Result based on spectra with known spin rate and orientation or images with at least 10 detectable (SNR>3) pixels. Size may be wrong by 30 percent.
* Q = 3 → Result based on basic (ellipsoid) shape model or extensive set of images/spectra. Size may be wrong by 20 percent.
* Q = 4 → Result based on advanced shape model. Secure result within the precision given.

Modifiers:
- In some cases, a trailing plus sign (+) or minus sign (-) is used to indicate a slightly better or worse quality than the unsigned value.
- In some cases, a trailing question mark (?) is used to indicate an ambiguity in pole orientation that yields discrepant size estimates.

Best practices:
- A size estimate based on limited bandwidth data with unknown spin rate and/or orientation is normally deemed inconclusive (Q=1).
- A size estimate based on high-SNR images with limited orientational coverage is normally deemed of low (Q=2) to moderate (Q=3) quality depending on the apparent regularity of the object's shape.
- The fractional uncertainty on volume is normally three times the fractional uncertainty on effective diameter. 
