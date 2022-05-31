# TMP36
This project was created to help enigneers, technicians, and hobbyist quicky get the TMP36 Low Voltage Temperature Sensor working in their own projects.



# Basic circuit used to gather characteristic data

![Simple Circuit](<Simple_Schematic.png>)


# Conclusions after testing this part

I have tested the TMP36GT9Z, TMP36GZ, TMP36G, and the TMP37FT9Z. 

Conclusion: 

Throw all of these away, and never buy a TMP35/TMP36/TMP37 again. This is the worst designed IC circuit I think I have ever seen. The ouptut jumps all over the place and it is extremely sensitive to the slightest electromagnetic radiation. Unpredictable. I was shocked at how bad this IC is. You cannot design a reliable circuit around this part.

# Recommendation after testing this part

Recommendation: 

Buy the MCP9701A-E/TO instead and never look back. The MCP9701A-E/TO behaves exactly the way you would expect. Solid as a rock. 

I will be putting up data from my test results of the MCP9701A-E/TO shortly, here: https://github.com/Joe0x7F/MCP9701A

The info will include a characteristic equation that you can use to design your circuits.
