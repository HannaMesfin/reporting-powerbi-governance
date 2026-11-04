Power Query 

Power Query transformations and reusable reporting logic for CS Reporting.

VC SMA Confidential Name Unblinding
Unblinds a confidential investment name when another investment with the same Fund Name Final has no blinding requirement.

The logic:
Treats only Client Blind in QR = "1" as blinded.
Treats blank, 0, and other values as having no blinding requirement.
Matches Fund Name Final without regard to case or surrounding spaces.
Keeps unmatched flagged investments confidential.
Removes the need to maintain a hardcoded replacement list.
See VC-SMA-Unblinding.html for the full documentation and interactive example
