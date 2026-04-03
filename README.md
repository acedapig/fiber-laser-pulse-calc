# fiber-laser-pulse-calc
Pulse Calculator and Settings Converter for Fiber Lasers

Usage of the tool:
Download and open the HTML file in a web browser. The app is capable of saving your user settings in your browser's cache for you to close and reopen later. The calculator tab is the default view.

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

The Parameter Converter tab will by default grab the current model selected in the calculator tab and input it as your source. You can then select another source to convert to or swap to go the other way.

Inputting settings will then give you a confidence value of converting the settings to this other source.
