# Coaxial-fed microstrip patch antenna

Microstrip patch antenna with a coaxial probe feed, designed in CST Studio Suite and targeted at the 2.4 GHz band. Feed-pin position and patch dimensions were tuned across several iterations to improve the impedance match.

## Results

Final design resonates at 2.56 GHz with S11 ≈ -38 dB and VSWR ≈ 1.03, checked across three mesh passes. An earlier iteration resonated at 2.7 GHz with a weaker match (S11 ≈ -10.5 dB); the feed position was adjusted to reach the final result.

## Files

- s11.s1p - exported S-parameter data (Touchstone format)
- s11_plot.png - S11 magnitude vs frequency
- vswr_plot.png - VSWR vs frequency
- geometry.png - model view from CST
- feed_detail.png - close-up of the coaxial pin and ground clearance

Tool: CST Studio Suite.
