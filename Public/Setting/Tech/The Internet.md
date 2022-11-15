
Any system that has a ICF can communicate with one other system. These ICFs tend to connect with a system that functions as a hub for ICF endpoints. That hub system then communicates with other hub systems, eventually leading to the target system.

A single packet has a transmission time of:

* About 5 milliseconds per hub + transmission time from start system location to start system ICF + end system ICF to end system location.

* To reduce communication delay between packet transfer from system location to the system's ICF, local ICFs will be constructed as well. Making that delay only be to the nearest ICF in the system.