# Post-Covid-Symptomps-Detector-System
This is an university project with my classmates for EEE-301, Digital Logic Design. The goal of this project is to identify COVID-19 suspects and recommend that they undergo COVID-19 testing.

This system was entirely built in analog circuitry. In this case, we constructed four, 7485 Comparator IC. There are two Comparator IC for Oxygen Level Saturation and two more for Forehead Temperature. We set one 7485 IC as the reference value and compare it to another 7485 IC. Follow the same steps to obtain the other objective.

When a person go through the gate, the results of the child circuits will go through a NAND Gate. We utilized a logic probe to identify the people who were present. Both findings will be deployed as inputs to the 4026 Seven Segment Counter IC, which will display the amount of suspects and notify the authorities for further surveillance.
