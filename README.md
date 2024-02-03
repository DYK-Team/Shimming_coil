# Shimming_Coil
1D shimming coil design and optimisation algorithm
by Dr. Yujie Zhao
University of St. Andrews, Scotland
https://yujiephysics.wordpress.com/2023/11/09/nmr-maget-shimming-and-current-driver-design/

Highlights:
In the project, our primary goal was not to develop a practical compensation system but to explore the mathematical methods, electronic and digital technologies required for future customized systems in our measurement installations.

Along this path, we have made significant progress:

➢Proposed a shimming coil architecture using a planar spiral coil system.

➢Tested Python algorithms for numerical optimization of functionals with a large number of variables.

➢Explored the Python symbolic calculus library SymPy, enabling complex calculations like derivatives.

➢Developed and tested a low-cost multi-channel PWM driver circuit with a current booster, facilitating the powering of numerous individual coils.

➢ Presented a scheme for testing electronic drivers using the Arduino microcontroller.

➢ Tested the MCP2221 USB-to-I2C adapter, allowing direct computer control of the multi-channel PWM drivers PCA9685 without
the need for a microcontroller.

➢ Demonstrated effective heat management of electronic devices using voltage regulators and transistors.

➢ Identified potential manufacturing technologies for planar spiral coils.

➢ Successfully manufactured a working prototype of a four-channel electronic driver. 

For more details, please read the report: "Design and optimisation of 1D shimming coils.pdf". The purpose of each project folder can be found in the report Appendix. You will have to tinker a little to install the Python libraries for MCP2221 and PCA9685. In the report we provide relevant links to the Adafruit website.
