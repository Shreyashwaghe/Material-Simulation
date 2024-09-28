# Material-Simulation
This material simulation project is part of the B. Tech Project Titled "Recrystallization Modelling using Monte Carlo Method"

Recrystallization can be defined as the formation of a new grain structure in a plastically deformed material. This recrystallization occurs through the formation and migration of high-angle boundaries. As plastic deformation increases, the material becomes thermodynamically unstable and this leads to recrystallization wherein new grains of relatively low stored energy are nucleated in the microstructure. By consuming the high-energy grains in their surroundings, these newly nucleated grains reduce the internally stored energy within the material, thereby increasing its thermodynamic stability.


In the below video, we see a 3D Material with 5x5x5 structure, recrystallizing to reduce its internal energy and leading to grain growth (Each grain orientation, is shown by a different colour)




https://github.com/user-attachments/assets/fae8b785-de01-4e25-9672-06dc9264e188


Below are the results from our python code implementation of the paper titled "Three-Dimensional Monte Carlo Simulation of Recrystallization in Silver" DOI 10.1109/BCGIn.2011.110
The Simulation was done for 100 Monte Carlo steps, with the additional logic of considering the minimum grain orientation angle, from the 24 symmetric rotational operations in the cubic system, as described by Kocks et. al. (Kocks, Fred & Tomé, Carlos & Wenk, H-R. (2000). Texture and Anisotropy. Preferred Orientations in Polycrystals and Their Effect on Material Properties Book).


