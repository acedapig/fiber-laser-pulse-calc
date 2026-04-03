# fiber-laser-pulse-calc
Pulse Calculator and Settings Converter for Fiber Lasers

This is based off of information from model specific manuals where I was able to take and pull information like:
- Rated Power
- Max Pulse Energy
- Pulse Width
- Cuttoff values per Pulse Width (MOPA)
- Beam Quality
- Beam Diameter

This information is then taken and then values are calculated for
- Pulse Energy at a given frequency and Pulse Width
- Average Output Power at a given Freqyency, Pulse, and Power Requested
- Peak Pulse Power
- Pulse Period

Then if the user inputs information for optics / speed you can also calculate: 
- Focused Spot
- Fluence
- Pulse Overlap
- Line Overlap
